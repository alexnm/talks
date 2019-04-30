Title: **Done in 0.0166666666 seconds**

Duration: 30min

Tags: Performance, Rendering, Frontend

**tl;dr**

In order to ensure a smooth, jank-free experience on the web, we need to render a constant stream of 60 frames per second. This means that the browser has 16 milliseconds to execute our code and render the changes on the screen. Let’s find out how the rendering pipeline works and how JavaScript and CSS might affect the rendering performance.

**Abstract**

In order to ensure a smooth, jank-free experience on the web, we need to render a constant stream of 60 frames per second. This means that the browser has 16 milliseconds to execute our code and render the changes on the screen. But what happens when we scroll and the navigation bar starts animating? What happens when we switch from one page to another or when we have to remove an element from a long list in the DOM? In this talk we will have a look at how JavaScript and CSS come together to render something on the screen and we will explore some tips and tricks that everyone can follow to improve the rendering performance of their web applications.

**Content and Outline**

We’re going to talk about the event loop and about the rendering pipeline. We will look at CSS rules from a different perspective and understand the concept of a CSS reflow / layout. We will also look into Browser APIs and their impact on performance. Throughout the talk, we will mention the benefits of modern frameworks, the advantage of using a virtual DOM based rendering library and we will learn how to use the Chrome Dev Tools to identify rendering bottlenecks and issues.

* Why do we get laggy websites?
* Event loop recap
* The advantages of a vDOM implementation
* How the rendering pipeline works
* Which CSS rules trigger which stages from the rendering pipeline
* The will-change property, how to use it
* setTimeout vs requestAnimationFrame
* offloading to webworkers
