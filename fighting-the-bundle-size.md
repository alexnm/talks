Title: **Fighting the Bundle Size**

Duration: 30min

Tags: Web Performance, Browsers, Tooling 

Are you aware of how much code you are actually shipping to your users? Is bundle size optimization part of your development pipeline? In this talk I will highlight some of the problems of bundling modern web applications and I will show you how you can measure and act upon the ever growing bundle sizes.

This talk focuses on modern web applications driven by frontend frameworks, module bundlers and build processes. It is structured around the idea of shaving off as many bytes as possible from your production code. Big bundles are paid multiple times in terms of performance costs, because you have to take into consideration both the download and the parse and compile times. In the end, less bytes mean faster load times.

We will go through some basic recipes for reducing the bundle size: from tree-shaking to code-splitting, from using micro frameworks like Preact to optimizing the compiled code with things like prepack or the google closure compile. Also, we will dive deep into browserland to see when and how we should ship polyfills together with our bundles. At the end of the talk, attendees should have a greater understanding of the standard tooling they are using (webpack, babel) and should be able to introduce some of the recipes in their own development process.

This is an approximate structure of the talk:
* Why performance matters - quick overview of the critical rendering path in modern web apps
* How JS is loaded, evaluated and executed
* Webpack & Babel - how they work together
* Webpack Bundler Analyzer
* Optimizing Webpack - tree shaking and scope hoisting
* Code Splitting
* Transpilling & Polyfills - when and how
* Looking ahead - JS as a compile target
