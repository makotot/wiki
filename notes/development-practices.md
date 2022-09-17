---
description: >-
  All things related to development that I would like to keep in my personal
  stock. Mostly web frontend related.
---

# Development Practices

![status](https://img.shields.io/badge/status-WIP-yellow?style=for-the-badge)

***

### Glossary

#### Design or Architecture

> So in short, Software architecture is more about the design of the entire system, while software design emphasizes on module / component / class level.
>
> https://stackoverflow.com/questions/704855/software-design-vs-software-architecture

***

### Coding Style / Guideline

#### Naming

> There are only two hard things in Computer Science: cache invalidation and naming things. -- Phil Karlton
>
> https://martinfowler.com/bliki/TwoHardThings.html

> Any fool can write code that a computer can understand. Good programmers write code that humans can understand.
>
> https://twitter.com/martinfowler/status/1067179181140844544

***

### Testing

> Write tests. Not too many. Mostly integration.
>
> https://twitter.com/rauchg/status/807626710350839808

> The more your tests resemble the way your software is used, the more confidence they can give you.
>
> https://twitter.com/kentcdodds/status/977018512689455106

***

### Architecture

> Software architecture is the art of drawing lines that I call boundaries. Those boundaries separate software elements from one another, and restrict those on one side from knowing about those on the other.
>
> https://www.oreilly.com/library/view/clean-architecture-a/9780134494272/ch17.xhtml

***

### Design

### Principle

#### YAGNI

> Always implement things when you actually need them, never when you just foresee that you need them.
>
> https://ronjeffries.com/xprog/articles/practices/pracnotneed/

#### KISS

> Keep it Short and Simple
>
> https://en.wikipedia.org/wiki/KISS\_principle

#### DRY

> Don't repeat yourself
>
> https://en.wikipedia.org/wiki/Don%27t\_repeat\_yourself

#### Principle Of Least Astonishment

> a component of a system should behave in a way that most users will expect it to behave.
>
> https://en.wikipedia.org/wiki/Principle\_of\_least\_astonishment

***

### Framework/Library

#### Redux

**Selector**

> Adding a separate selector function for every single field is not a good idea! That ends up turning Redux into something resembling a Java class with getter/setter functions for every field. It's not going to improve the code, and it's probably going to make the code worse - maintaining all those extra selectors is a lot of additional effort, and it will be harder to trace what values are being used where.
>
> https://redux.js.org/usage/deriving-data-selectors#balance-selector-usage

***

### Quotes

> The Best Code is No Code At All
>
> https://blog.codinghorror.com/the-best-code-is-no-code-at-all/

> duplication is far cheaper than the wrong abstraction
>
> https://sandimetz.com/blog/2016/1/20/the-wrong-abstraction

***

### Resources

#### Project

* [elsewhencode/project-guidelines: A set of best practices for JavaScript projects](https://github.com/elsewhencode/project-guidelines)
* Repository
  * [joelparkerhenderson/monorepo-vs-polyrepo: Monorepo vs. polyrepo: architecture for source code management (SCM) version control systems (VCS)](https://github.com/joelparkerhenderson/monorepo-vs-polyrepo)
  * [Monorepo Explained](https://monorepo.tools/)

#### Coding Style/Guideline

* [Kristories/awesome-guidelines: A curated list of high quality coding style conventions and standards.](https://github.com/Kristories/awesome-guidelines)
* [kettanaito/naming-cheatsheet: Comprehensive language-agnostic guidelines on variables naming. Home of the A/HC/LC pattern.](https://github.com/kettanaito/naming-cheatsheet)
* [RichardLitt/awesome-styleguides: A list of styleguides](https://github.com/RichardLitt/awesome-styleguides)
* [dustinspecker/awesome-eslint: A list of awesome ESLint plugins, configs, etc.](https://github.com/dustinspecker/awesome-eslint)

#### Architecture/Design/Principle

* [mehdihadeli/awesome-software-architecture: A curated list of awesome articles, videos, and other resources to learn and practice software architecture, patterns, and principles.](https://github.com/mehdihadeli/awesome-software-architecture)
* [simskij/awesome-software-architecture: A curated list of resources on software architecture](https://github.com/simskij/awesome-software-architecture)
* [ryanmcdermott/3rs-of-software-architecture: A guide on how to write readable, reusable, and refactorable software](https://github.com/ryanmcdermott/3rs-of-software-architecture)
* [feature-sliced/documentation: 🍰 Architectural design methodology for Frontend projects](https://github.com/feature-sliced/documentation)
* [lxsmnsyc/awesome-islands: All about Islands Architecture and Partial Hydration](https://github.com/lxsmnsyc/awesome-islands)
* [Patterns.dev - Modern Web App Design Patterns](https://www.patterns.dev/)
* [stemmlerjs/software-design-and-architecture-roadmap: 🧱 The software design and architecture roadmap for any developer](https://github.com/stemmlerjs/software-design-and-architecture-roadmap)
* [Top 10 Architecture Characteristics / Non-Functional Requirements with Cheatsheet | by Love Sharma | Dev Genius](https://blog.devgenius.io/top-10-architecture-characteristics-non-functional-requirements-with-cheatsheat-7ad14bbb0a9b)
* [Self-documenting Architecture. One of the biggest time costs in… | by Nick Tune | Strategy, Architecture, Continuous Delivery, and DDD | Medium](https://medium.com/nick-tune-tech-strategy-blog/self-documenting-architecture-80c8c2429cb8)
* [Clean Architecture on Frontend - DEV Community 👩‍💻👨‍💻](https://dev.to/bespoyasov/clean-architecture-on-frontend-4311)
* [Software Architecture Cheat Sheet for Daily Usage | by Ali Zeynalli | Medium](https://azeynalli1990.medium.com/software-architecture-cheat-sheet-for-daily-usage-9923922ea75b)
* [Developer-Y/Scalable-Software-Architecture: Collection of tech talks, papers and web links on Distributed Systems, Scalability and System Design.](https://github.com/Developer-Y/Scalable-Software-Architecture)
* [Frontend Architecture at Scale for Large Organizations | by Daniel Ostapenko | The Startup | Medium](https://medium.com/swlh/frontend-architecture-in-scale-for-large-organizations-593930ed10cd)
* [donnemartin/system-design-primer: Learn how to design large-scale systems. Prep for the system design interview. Includes Anki flashcards.](https://github.com/donnemartin/system-design-primer)
* Design Patterns
  * [DovAmir/awesome-design-patterns: A curated list of software and architecture related design patterns.](https://github.com/DovAmir/awesome-design-patterns)
  * [kamranahmedse/design-patterns-for-humans: An ultra-simplified explanation to design patterns](https://github.com/kamranahmedse/design-patterns-for-humans)
  * [sohamkamani/javascript-design-patterns-for-humans: An ultra-simplified explanation of design patterns implemented in javascript](https://github.com/sohamkamani/javascript-design-patterns-for-humans)
  * [torokmark/design\_patterns\_in\_typescript: Design pattern implementations in TypeScript](https://github.com/torokmark/design\_patterns\_in\_typescript)
* SOLID
  * [SOLID Principles: The Software Developer's Framework to Robust & Maintainable Code \[with Examples\] | Khalil Stemmler](https://khalilstemmler.com/articles/solid-principles/solid-typescript/)
* DDD
  * [heynickc/awesome-ddd: A curated list of Domain-Driven Design (DDD), Command Query Responsibility Segregation (CQRS), Event Sourcing, and Event Storming resources](https://github.com/heynickc/awesome-ddd)
  * [Value Objects - DDD w/ TypeScript | Khalil Stemmler](https://khalilstemmler.com/articles/typescript-value-object/)
* Micro Frontends
  * [rajasegar/awesome-micro-frontends: An Awesome list of posts, videos and tutorials on Micro Frontends](https://github.com/rajasegar/awesome-micro-frontends)
  * [Micro Frontends](https://martinfowler.com/articles/micro-frontends.html)
  * [Micro-frontends decisions framework | by Luca Mezzalira | Medium](https://medium.com/@lucamezzalira/micro-frontends-decisions-framework-ebcd22256513)
* Plugin Architecture
  * [Plug-in Architecture. and the story of the data pipeline… | by Omar Elgabry | OmarElgabry's Blog | Medium](https://medium.com/omarelgabrys-blog/plug-in-architecture-dec207291800)
* ADR
  * [joelparkerhenderson/architecture-decision-record: Architecture decision record (ADR) examples for software planning, IT leadership, and template documentation](https://github.com/joelparkerhenderson/architecture-decision-record)
* :jp:
  * [Katsukiniwa/awesome-software-design-ja: 日本語でのソフトウェア開発・設計に関する記事や書籍をまとめたリポジトリです](https://github.com/Katsukiniwa/awesome-software-design-ja)

#### Testing

* [NoriSte/ui-testing-best-practices: The largest UI testing best practices list (last update: May 2021)](https://github.com/NoriSte/ui-testing-best-practices)
* [goldbergyoni/javascript-testing-best-practices: 📗🌐 🚢 Comprehensive and exhaustive JavaScript & Node.js testing best practices (April 2022)](https://github.com/goldbergyoni/javascript-testing-best-practices)
* [TheJambo/awesome-testing: A curated list of testing resources](https://github.com/TheJambo/awesome-testing)
* [index at XUnitPatterns.com](http://xunitpatterns.com/)
* [atinfo/awesome-test-automation: A curated list of awesome test automation frameworks, tools, libraries, and software for different programming languages. Sponsored by http://sdclabs.com](https://github.com/atinfo/awesome-test-automation)
* [mawrkus/js-unit-testing-guide: 📙 A guide to unit testing in Javascript](https://github.com/mawrkus/js-unit-testing-guide)
* [abhivaikar/howtheytest: A collection of public resources about how software companies test their software](https://github.com/abhivaikar/howtheytest)
  * :jp:
    * [tadashi0713/howtheytest-jp: 日本のソフトウェア企業のテスト・テスト自動化に関する資料をまとめています](https://github.com/tadashi0713/howtheytest-jp)
* [Should I Test Private Methods?](http://shoulditestprivatemethods.com/)
* [mojoaxel/awesome-regression-testing: 🕶️ A curated list of resources around the topic: visual regression testing](https://github.com/mojoaxel/awesome-regression-testing)

#### UI

* [Pure UI](https://rauchg.com/2015/pure-ui)
* [Pure UI Control. This month marks 10 years that I’ve… | by Adam Solove | Medium](https://asolove.medium.com/pure-ui-control-ac8d1be97a8d)

#### Performance

* [thedaviddias/Front-End-Performance-Checklist: 🎮 The only Front-End Performance Checklist that runs faster than the others](https://github.com/thedaviddias/Front-End-Performance-Checklist)

#### A11y

* [Accessibility Myths](https://a11ymyths.com/)

#### Code Review

* [ryanmcdermott/code-review-tips: Common problems to look for in a code review](https://github.com/ryanmcdermott/code-review-tips)

#### Language

* JavaScript :elephant:
  * [JavaScript's Memory Management Explained | Felix Gerschau](https://felixgerschau.com/javascript-memory-management/)

#### Framework/Library

* React ⚛️
  * [Tao of React - Software Design, Architecture & Best Practices | Alex Kondov - Software Engineer](https://alexkondov.com/tao-of-react/)
  * [alan2207/bulletproof-react: 🛡️ ⚛️ A simple, scalable, and powerful architecture for building production ready React applications.](https://github.com/alan2207/bulletproof-react)
  * [kudos-dude/react-best-practices: A comprehensive reference guide to kickstart your React architecting career!](https://github.com/kudos-dude/react-best-practices)
  * [vasanthk/react-bits: ✨ React patterns, techniques, tips and tricks ✨](https://github.com/vasanthk/react-bits)
  * [mithi/react-philosophies: 🧘 Things I think about when I write React code 🧘](https://github.com/mithi/react-philosophies)
  * [themithy/react-design-patterns: An attempt to implement software design patterns in React](https://github.com/themithy/react-design-patterns)
* Redux
  * [Style Guide | Redux](https://redux.js.org/style-guide/)
* GraphQL
  * [Principled GraphQL - Principled GraphQL](https://principledgraphql.com/)

#### Books :book:

* [Amazon | Micro Frontends in Action | Geers, Michael | Software Development](https://www.amazon.co.jp/gp/product/1617296872/)
* :jp:
  * [レガシーコードからの脱却 ―ソフトウェアの寿命を延ばし価値を高める9つのプラクティス | David Scott Bernstein, 吉羽 龍太郎, 永瀬 美穂, 原田 騎郎, 有野 雅士 |本 | 通販 | Amazon](https://www.amazon.co.jp/%E3%83%AC%E3%82%AC%E3%82%B7%E3%83%BC%E3%82%B3%E3%83%BC%E3%83%89%E3%81%8B%E3%82%89%E3%81%AE%E8%84%B1%E5%8D%B4-%E2%80%95%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2%E3%81%AE%E5%AF%BF%E5%91%BD%E3%82%92%E5%BB%B6%E3%81%B0%E3%81%97%E4%BE%A1%E5%80%A4%E3%82%92%E9%AB%98%E3%82%81%E3%82%8B9%E3%81%A4%E3%81%AE%E3%83%97%E3%83%A9%E3%82%AF%E3%83%86%E3%82%A3%E3%82%B9-David-Scott-Bernstein/dp/4873118867/ref=d\_msx\_wsirn\_v1\_sccl\_2\_5/356-5282683-1472320?pd\_rd\_w=J4KiQ\&content-id=amzn1.sym.72eb91a1-81d6-4ae4-8b91-3e94bd01608f\&pf\_rd\_p=72eb91a1-81d6-4ae4-8b91-3e94bd01608f\&pf\_rd\_r=7AQ6S5QM33E4A13SMP7M\&pd\_rd\_wg=gkgFt\&pd\_rd\_r=bd4b7bc3-caf8-464f-9b72-3c40a95504d9\&pd\_rd\_i=4873118867\&psc=1)
  * [ソフトウェアアーキテクチャの基礎 ―エンジニアリングに基づく体系的アプローチ | Mark Richards, Neal Ford, 島田 浩二 |本 | 通販 | Amazon](https://www.amazon.co.jp/%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2%E3%82%A2%E3%83%BC%E3%82%AD%E3%83%86%E3%82%AF%E3%83%81%E3%83%A3%E3%81%AE%E5%9F%BA%E7%A4%8E-%E2%80%95%E3%82%A8%E3%83%B3%E3%82%B8%E3%83%8B%E3%82%A2%E3%83%AA%E3%83%B3%E3%82%B0%E3%81%AB%E5%9F%BA%E3%81%A5%E3%81%8F%E4%BD%93%E7%B3%BB%E7%9A%84%E3%82%A2%E3%83%97%E3%83%AD%E3%83%BC%E3%83%81-Mark-Richards/dp/4873119820/ref=d\_pd\_vtp\_sccl\_3\_5/356-5282683-1472320?pd\_rd\_w=RggxX\&content-id=amzn1.sym.cbb45385-7b99-44b7-a528-bff5ddaa153d\&pf\_rd\_p=cbb45385-7b99-44b7-a528-bff5ddaa153d\&pf\_rd\_r=SWB9GB3FDWN27NQTYN9T\&pd\_rd\_wg=wNgco\&pd\_rd\_r=39a6b093-a82c-4591-a7a5-5817514530c8\&pd\_rd\_i=4873119820\&psc=1)
  * [ソフトウェアアーキテクトが知るべき97のこと | 鈴木 雄介, Richard Monson-Haefel, 鈴木 雄介, 長尾 高弘 |本 | 通販 | Amazon](https://www.amazon.co.jp/%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2%E3%82%A2%E3%83%BC%E3%82%AD%E3%83%86%E3%82%AF%E3%83%88%E3%81%8C%E7%9F%A5%E3%82%8B%E3%81%B9%E3%81%8D97%E3%81%AE%E3%81%93%E3%81%A8-%E9%88%B4%E6%9C%A8-%E9%9B%84%E4%BB%8B/dp/4873114292)
    * [ソフトウェアアーキテクトが知るべき97のこと](https://xn--97-273ae6a4irb6e2h2ia0cn0g4a2txf4ah5wo4af612j.com/)
  * [Clean Architecture 達人に学ぶソフトウェアの構造と設計 | Robert C.Martin, 角 征典, 高木 正弘 |本 | 通販 | Amazon](https://www.amazon.co.jp/Clean-Architecture-%E9%81%94%E4%BA%BA%E3%81%AB%E5%AD%A6%E3%81%B6%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2%E3%81%AE%E6%A7%8B%E9%80%A0%E3%81%A8%E8%A8%AD%E8%A8%88-Robert-C-Martin/dp/4048930656)
  * [プリンシプル オブ プログラミング3年目までに身につけたい一生役立つ101の原理原則 | 上田 勲 |本 | 通販 | Amazon](https://www.amazon.co.jp/%E3%83%97%E3%83%AA%E3%83%B3%E3%82%B7%E3%83%97%E3%83%AB-%E3%82%AA%E3%83%96-%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B03%E5%B9%B4%E7%9B%AE%E3%81%BE%E3%81%A7%E3%81%AB%E8%BA%AB%E3%81%AB%E3%81%A4%E3%81%91%E3%81%9F%E3%81%84%E4%B8%80%E7%94%9F%E5%BD%B9%E7%AB%8B%E3%81%A4101%E3%81%AE%E5%8E%9F%E7%90%86%E5%8E%9F%E5%89%87-%E4%B8%8A%E7%94%B0-%E5%8B%B2/dp/4798046140)
  * [達人プログラマー(第2版): 熟達に向けたあなたの旅 | Thomas,David, Hunt,Andrew, 雅章, 村上 |本 | 通販 | Amazon](https://www.amazon.co.jp/%E9%81%94%E4%BA%BA%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9E%E3%83%BC-%E7%AC%AC2%E7%89%88-%E7%86%9F%E9%81%94%E3%81%AB%E5%90%91%E3%81%91%E3%81%9F%E3%81%82%E3%81%AA%E3%81%9F%E3%81%AE%E6%97%85-David-Thomas/dp/4274226298/ref=pd\_lpo\_2?pd\_rd\_i=4274226298\&psc=1)
  * [良いコード/悪いコードで学ぶ設計入門 ―保守しやすい 成長し続けるコードの書き方 | 仙塲 大也 |本 | 通販 | Amazon](https://www.amazon.co.jp/%E8%89%AF%E3%81%84%E3%82%B3%E3%83%BC%E3%83%89-%E6%82%AA%E3%81%84%E3%82%B3%E3%83%BC%E3%83%89%E3%81%A7%E5%AD%A6%E3%81%B6%E8%A8%AD%E8%A8%88%E5%85%A5%E9%96%80-%E2%80%95%E4%BF%9D%E5%AE%88%E3%81%97%E3%82%84%E3%81%99%E3%81%84-%E6%88%90%E9%95%B7%E3%81%97%E7%B6%9A%E3%81%91%E3%82%8B%E3%82%B3%E3%83%BC%E3%83%89%E3%81%AE%E6%9B%B8%E3%81%8D%E6%96%B9-%E4%BB%99%E5%A1%B2/dp/4297127830/ref=pd\_rhf\_d\_dp\_s\_pd\_crcd\_sccl\_2\_2/356-5282683-1472320?pd\_rd\_w=ZEftS\&content-id=amzn1.sym.f6807b6a-a51f-484d-a903-9221ae683054\&pf\_rd\_p=f6807b6a-a51f-484d-a903-9221ae683054\&pf\_rd\_r=E3WQ3BQDZPSYG5E1MD31\&pd\_rd\_wg=AIyVw\&pd\_rd\_r=e4fbcf9f-9fd8-4c1f-be20-29d909057d91\&pd\_rd\_i=4297127830\&psc=1)
  * [Clean Code アジャイルソフトウェア達人の技 | Robert C.Martin, 花井 志生 |本 | 通販 | Amazon](https://www.amazon.co.jp/gp/product/4048930591/)
  * [チームトポロジー 価値あるソフトウェアをすばやく届ける適応型組織設計 | マシュー・スケルトン, マニュエル・パイス, 原田 騎郎, 永瀬 美穂, 吉羽 龍太郎 |本 | 通販 | Amazon](https://www.amazon.co.jp/%E3%83%81%E3%83%BC%E3%83%A0%E3%83%88%E3%83%9D%E3%83%AD%E3%82%B8%E3%83%BC-%E4%BE%A1%E5%80%A4%E3%81%82%E3%82%8B%E3%82%BD%E3%83%95%E3%83%88%E3%82%A6%E3%82%A7%E3%82%A2%E3%82%92%E3%81%99%E3%81%B0%E3%82%84%E3%81%8F%E5%B1%8A%E3%81%91%E3%82%8B%E9%81%A9%E5%BF%9C%E5%9E%8B%E7%B5%84%E7%B9%94%E8%A8%AD%E8%A8%88-%E3%83%9E%E3%82%B7%E3%83%A5%E3%83%BC%E3%83%BB%E3%82%B9%E3%82%B1%E3%83%AB%E3%83%88%E3%83%B3/dp/4820729632/ref=d\_msx\_wsirn\_v1\_sccl\_2\_32/356-5282683-1472320?pd\_rd\_w=0KpuO\&content-id=amzn1.sym.72eb91a1-81d6-4ae4-8b91-3e94bd01608f\&pf\_rd\_p=72eb91a1-81d6-4ae4-8b91-3e94bd01608f\&pf\_rd\_r=4DDFJXYJW4S8DQZV6DTA\&pd\_rd\_wg=R5VC1\&pd\_rd\_r=5d70d0a1-320b-47dc-ab5f-b310923d1982\&pd\_rd\_i=4820729632\&psc=1)

### Blog

* [Bliki](https://martinfowler.com/bliki/)
  * :jp: [Martin Fowler's Bliki (ja)](https://bliki-ja.github.io/)
* [The Kent C. Dodds Blog](https://kentcdodds.com/blog)

#### Misc

* [Technology Radar | An opinionated guide to technology frontiers | Thoughtworks](https://www.thoughtworks.com/radar)
* [binhnguyennus/awesome-scalability: The Patterns of Scalable, Reliable, and Performant Large-Scale Systems](https://github.com/binhnguyennus/awesome-scalability)
* [trekhleb/state-of-the-art-shitcode: 💩State-of-the-art shitcode principles your project should follow to call it a proper shitcode](https://github.com/trekhleb/state-of-the-art-shitcode)
* [kelseyhightower/nocode: The best way to write secure and reliable applications. Write nothing; deploy nowhere.](https://github.com/kelseyhightower/nocode)
* [Component Driven User Interfaces](https://www.componentdriven.org/)
* [sturobson/Awesome-Design-Tokens: A list of resources on all things to do with Design Tokens](https://github.com/sturobson/Awesome-Design-Tokens)
* [leonardomso/33-js-concepts: 📜 33 JavaScript concepts every developer should know.](https://github.com/leonardomso/33-js-concepts)
* [castorm/engineering-principles: Collection of software engineering concepts, principles, laws, practices, patterns and properties worth having present in the software engineer’s practice.](https://github.com/castorm/engineering-principles)
* [futurice/backend-best-practices: An evolving description of general best practices for backend development.](https://github.com/futurice/backend-best-practices)
* [Unix philosophy - Wikipedia](https://en.wikipedia.org/wiki/Unix\_philosophy)
* [EbookFoundation/free-programming-books: Freely available programming books](https://github.com/EbookFoundation/free-programming-books)
* [thedaviddias/Front-End-Checklist: 🗂 The perfect Front-End Checklist for modern websites and meticulous developers](https://github.com/thedaviddias/Front-End-Checklist)
