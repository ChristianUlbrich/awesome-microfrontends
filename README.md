# Awesome Micro Frontends [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated and hopefully awe-some list about Micro Frontends.

## Intro
Micro Frontends are an _architectural pattern_, just as Microservices are. There are many ways to achieve a Micro Frontend architecture. This list presents the essential and required material to come up with your very own Micro Frontend approach.

> In this approach, the web application is broken down into its features, and each feature is owned, frontend to backend, by a different team. This ensures that every feature is developed, tested and deployed independently from other features. Multiple techniques exist to recombine the features — sometimes as pages, sometimes as components — into a cohesive user experience. [Source](https://www.thoughtworks.com/radar/techniques/micro-frontends)

## Contents

- [Concepts](#concepts)
    - [Components](#components)
- [Tooling](#tooling)
    - [Building Blocks](#building-blocks)
    - [Frameworks](#tooling)
- [Talks](#talks)
- [Meta](#meta)
    - [Other lists](#other-lists)
    - [Books](#books)

## Concepts

Blog posts and web sites that are talking about the general concepts for a Micro Frontend architecture.

- [micro-frontends.org](https://micro-frontends.org/) - framework agnostic introduction to Micro Frontends.
- [Micro frontends—a microservice approach to front-end web development
](https://medium.com/@tomsoderlund/micro-frontends-a-microservice-approach-to-front-end-web-development-f325ebdadc16) - a motivation for Micro Frontends.

### Components
- [Bringing componentization to the web](https://blogs.windows.com/msedgedev/2015/07/14/bringing-componentization-to-the-web-an-overview-of-web-components/) - **must read** that holds true in many aspects even today



## Tooling

### Building Blocks
#### Web Components
- [Custom Element V1](https://developers.google.com/web/fundamentals/web-components/customelements) - The Custom Elements V1 API is the most important API you need for building Web Components
- [StencilJS](https://stenciljs.com/) - StencilJS is a specific framework for building Web Components declaratively with modern TypeScript.
- [LitElement](https://github.com/Polymer/lit-element/) - super-recent small library from Google to bootstrap Web Components

#### Event Bus
- [Postal.js](https://github.com/postaljs/postal.js) _"loosely AMQP inspired EventBus for the browser"_
#### Distribution
- [unpkg.com](https://unpkg.com) - allows for deep-linking into the npm registry and thus to consume components off npm

### Frameworks

- [Mosaic](https://www.mosaic9.org/) - Project Mosaic is Zalando's take on micro frontends and is a complete framework for it.
- [single-spa](https://single-spa.js.org/) - Canopy's approach on micro frontends is about composing multiple SPAs.
- [OpenComponents](https://opencomponents.github.io/) - _"an open-source, "batteries included" micro frontends framework"_
- [Polymer Project](https://www.polymer-project.org/) - Google's take on building Web Components that still has some nice tooling 

### Graveyard
- [Polymer Project](https://www.polymer-project.org/) - Google's take on building Web Components won't be used for its upcoming Material Web Components and that says it all

## Meta
- [A Software Architect's Approach...](https://www.softwarearchitekt.at/post/2017/12/28/a-software-architect-s-approach-towards-using-angular-and-spas-in-general-for-microservices-aka-microfrontends.aspx) - decision tree, whether you need Micro Frontends (with Web Components)

### Other Lists
- [Micro Frontends by Elisabeth Engel](https://micro-frontends.zeef.com/elisabeth.engel?ref=elisabeth.engel&share=ee53d51a914b4951ae5c94ece97642fc) - closed curated list with tracking links for micro frontends

### Books
- [Micro Frontends in Action](https://www.manning.com/books/micro-frontends-in-action)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Christian Ulbrich has waived all copyright and
related or neighboring rights to this work.
