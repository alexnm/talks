Title: **Optimizing the Critical Rendering Path (in React)**

Duration: 30min

Links: [**slides**](https://slides.com/alexmoldovan/optimizing-the-critical-rendering-path#/) | [**video**](https://www.youtube.com/watch?v=j0c8UnfIQzQ)

Tags: Web Performance, React, Critical Rendering Path 

One of the crucial elements of performance is to ship relevant content to your users as soon as possible. But in modern web applications, figuring out what to ship and what to prioritize can be hard. Framework driven applications have the big disadvantage of being pretty heavy for the initial load. We will start from understanding how the browser works, then we will explain what the critical rendering path is and how we can optimize it. Expect a talk full of valuable resources and ideas that one can use to improve the performance of a modern web application, with a case study on a React powered application.

So you’re building this exciting new web application powered by React. But when you ship it to your users, you realize that they might have a bad experience loading the app. There are a lot of variables in the mix, from the internet connection to the performance of the device and of course to the browser of choice. Loading a React based application for the first time can be pretty slow and the first experience with your application can be crucial in the decision to use your service or not! Performance is not something that you handle reactively after you ship the application, performance should be baked into your software development process and your team should embrace performance optimization techniques as part of their working culture. Let’s find out together which are these techniques and how to better integrate them into your workflow

This talk will roughly cover:
* How the browser loads a traditional web application
* What is the critical rendering path and why it matters
* Why server rendering is crucial for optimizing the CRP
* Deferring JavaScript execution
* Using browser hints to speed up the initial load time (ex: preload, prefetch-dns)
* How to lazy load below the fold content
* Image optimization techniques
