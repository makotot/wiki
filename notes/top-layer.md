# top layer



### はじめに

[スタッキングコンテキスト](https://developer.mozilla.org/ja/docs/Web/CSS/CSS\_Positioning/Understanding\_z\_index/The\_stacking\_context)を理解して、`z-index`をうまく使いこなして、実現したいレイアウトを実装するのは苦労することが多いものかなと思う。 今後、`z-index`の値を`9999`のようにするのではなく、よりコントロールが容易な「top layer」というものが主流になり得るかもしれないので、確認する。

### top layerとは？

[Meet the top layer: a solution to z-index:10000](https://developer.chrome.com/blog/what-is-the-top-layer/)にある文章から引用させていただくと、

> The top layer sits above its related document in the browser viewport, and each document has one associated top layer.
>
> https://developer.chrome.com/blog/what-is-the-top-layer/

や、

> * Top layer is outside of the `document` flow.
> * `z-index` has no effect in the top layer.
> * Each element in the top layer has a styleable `::backdrop` pseudo-element.
> * Each element and `::backdrop` generates a new stacking context.
> * Elements in the top layer are stacked in the order they appear in the set. The last one in, appears on top. If you want to promote an element, remove it, and add it again.
>
> https://developer.chrome.com/blog/what-is-the-top-layer/

のように記述があり、

* ドキュメントにつき1つだけの、ブラウザのビューポートにおけるドキュメントの最上位へと位置するもの
* [ドキュメント フロー](https://soulandwolf.com.au/blog/what-is-document-flow/)に含まれない
* top layerに含まれる要素毎で`::backdrop`擬似要素を持つ
* top layerに含まれる要素毎とその`::backdrop`毎にスタッキングコンテキストを生成
* top layerに含まれる要素は後方にあるものが優先されて順番に重なる

というようなものになる。 なので、重ね順を上位にして表示したいものを常にtop layerへと（既に追加済みの場合は1度削除した上で）追加すれば良いという単純なルールなると思う。

他にも以下のような特徴がある。

* top layerにおいて`z-index`は影響がない
* top layerの要素は、親要素からの`overflow`や`opacity`の影響も受けない
* top layerの要素の祖先の要素が`display: none;`である場合、top layerの要素およびその`::backdrop`はレンダリングされない

### top layerとなるもの

以下のものがtop layerとなり得る。

* fullscreen
* `<dialog />`
* `popup`

### 参考

* [Meet the top layer: a solution to z-index:10000 - Chrome Developers](https://developer.chrome.com/blog/what-is-the-top-layer/)
* [Fullscreen API Standard](https://fullscreen.spec.whatwg.org/#top-layer)
* [CSS）z-indexのベストプラクティスを考える](https://zenn.dev/catnose99/articles/2f1be29dd203c10dff01)
* [君は真に理解しているか？z-indexとスタッキングコンテキストの関係 - ICS MEDIA](https://ics.media/entry/200609/)
* [What's New In DevTools (Chrome 105) - Chrome Developers](https://developer.chrome.com/blog/new-in-devtools-105/#top-layer)
