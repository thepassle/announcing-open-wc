<p align="center">
<img align="center" width="250" alt="open-wc logo" src="https://raw.githubusercontent.com/open-wc/open-wc/master/docs/.vuepress/public/hero.png"></img>
</p>

# Announcing open-wc

## Open Web Component Recommendations

Hi all! 👋 

We are `open-wc`, a collective of open source and web component enthusiasts. We consider it our goal to empower everyone with a powerful and battle-tested setup for creating and sharing open source web components.

Many web developers have experienced the dreaded "Javascript Fatigue". With our recommendations, we hope you'll enjoy the peace of mind that comes from having a well-known default solution for almost everything. From IDE to CI, open-wc has got you covered.

We want web component development to be accessible and approachable for everyone, regardless of your background or previous experience. Therefore, our recommendations aim to be easy to use, be ready to use, and provide that "it just works" developer experience we all crave for the various aspects of web component development.

We strongly believe that staying close to browser standards will be the best long term investment for your code. It is the basis for all our recommendations, and it means that sometimes we will not recommend a popular feature or functionality. It also means we can be faster to adopt and recommend new browser standards.


## Why Web Components

In the last several years, the component-based model for web application development was popularized, and the JavaScript community blossomed with a wide variety of libraries and approaches. Work on standardizing the web’s native component model began at Google in 2012, and after several years of open development, was successfully implemented across all major browsers in 2019. At the time of writing, over 10% of all page views contain web components.

We believe web components provide a standards-based solution to problems like reusability, interopability, and encapsulation. Furthermore, we believe using the browser's native component model will increase the longevity of your application. The web has an extremely strong tradition of backwards-compatibility, as standards bodies have consistently gone out of their way to maintain legacy APIs. 

At `open-wc` you'll find anything you might need to get started developing web components.

## Developing

In our [developing](https://open-wc.org/developing/) section you'll find anything you need to know about writing your code; from practical code demos, to accessibility, to mixins, to tutorials and blog posts.

We have a wide range of interactive demo's available to help you get started writing code quickly:

[![demos](https://i.imgur.com/CHs2d9a.png)](https://open-wc-lit-demos.stackblitz.io/)

If you want to learn more about web components first, we recommend the following blog posts to give you a solid basis to start developing web components:

- [Lets Build Web Components!](https://dev.to/bennypowers/lets-build-web-components-part-1-the-standards-3e85) by Benny Powers
- [Web Components: from Zero to Hero]() by Pascal Schilp

## Testing

Not only do we provide a [testing setup](https://open-wc.org/testing/testing-karma.html) with Karma, Browserstack, and Wallaby, we also provide a set of testing helpers that help you:

### Make fixtures:
![fixtures](https://i.imgur.com/ettoUME.png)
### Compare DOM:
![compare-dom](https://i.imgur.com/pjGezjL.png)
### Make sure batched updates are finished:
![timing](https://i.imgur.com/iyE0IKf.png)
### Define multiple custom elements:
![definece](https://i.imgur.com/lHUO7BO.png)

## App Starter

Many developers have experienced what has often been described as "JavaScript Fatigue", the overwhelming feeling of having to keep up with every new technology in the JavaScript ecosystem. JavaScript tooling can have an intimidating learning curve and can often be frustrating to configure. What are the right tools? Which tools should I be using? How do these tools work?

Our recommendations aim to relieve you some of that painful setup so you can skip right to the fun part; development. So if you want to get straight to developing, with a powerful setup that leverages the best of browser standards in no time, our [open-wc-app-starter](https://github.com/open-wc/open-wc-starter-app) might be for you!

[![app-starter](https://i.imgur.com/HMiq3b4.png)](https://github.com/open-wc/open-wc-starter-app)

Our open-wc-app-starter will set you up with a full configuration, with the following features:

- **Module resolution**
- **Automatic module type selection**
- **HTML, JS and CSS minifications**
- **es2015 and es5 output**
	- Using [webpack-babel-multi-target-plugin](https://www.npmjs.com/package/webpack-babel-multi-target-plugin), our build outputs an es5 and es2015 version of your app. Using the [nomodule trick](https://jakearchibald.com/2017/es-modules-in-browsers/), we can serve es2015 code on modern browsers and es5 on older browsers (IE11 specifically). This significantly reduces the size of your app on modern browsers.
- **No regenerator runtime / transform**
- **Polyfills by usage**
	- Language polyfills are added based on browser support and usage. This leads to a significantly smaller initial bundle of your app.
- **Syntax and javascript APIs**
	- Our config only supports standard javascript syntax and browser APIs. We support stage 3 proposals when they add significant value and are easy to support without major performance penalties. Some of the proposals we support are:
		- Dynamic import
		- import.meta.url
- **Testing suite with Karma**
- **Linting with ESLint, Prettier and commitlint**

You can find more documentation on our `open-wc-app-starter` [here](https://github.com/open-wc/open-wc-starter-app). We try to provide the best, user friendly set up available and your feedback is extremely valuable to us, so if you feel like anything is missing or you have any kind of feedback, please feel free to create an issue on our repo.

## And much, much more

Other recommendations include anything betwixt and between: [linting](https://open-wc.org/linting/), [demoing](https://open-wc.org/demoing/), [building](https://open-wc.org/building/), [publishing](https://open-wc.org/publishing/) and [automating](https://open-wc.org/automating/). We also have a fleet of [generators](https://open-wc.org/developing/generator) to plug and play any of our setups in your current project.

If you're interested in learning more about our philosophy and the rationale for our recommendations, you can do so [here](https://open-wc.org/about/).

It is our goal to help you get set up as quickly, and effortlessly as possible. If you feel like our recommendations are missing something, feel free to contact us. Please note that our recommendations and best practices are subject to change and may evolve over time.


## Join the conversation!

We'd love to hear any feedback or questions you might have. You can reach us at:

- Feel free to open an issue on our [Github](https://github.com/open-wc/open-wc) if you have a question or feedback.

- You can also find us on the Polymer slack in the [#open-wc](https://polymer.slack.com/messages/CE6D9DN05) channel.
You can join the Polymer slack by visiting [this link](https://join.slack.com/t/polymer/shared_invite/enQtNTAzNzg3NjU4ODM4LTkzZGVlOGIxMmNiMjMzZDM1YzYyMzdiYTk0YjQyOWZhZTMwN2RlNjM5ZDFmZjMxZWRjMWViMDA1MjNiYWFhZWM).

- You can find our recommendations and documentation over at: [open-wc](https://open-wc.org).

<br>
<p align="center">
🚽 Made with love by <a href="https://github.com/open-wc/open-wc">open-wc</a>. </p>
