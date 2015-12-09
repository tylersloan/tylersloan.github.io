---
layout: project
bodyClass: project
title: "Southeastern Mills"
orderId: 001
builtIn: "Summer 2015"
client: "Southeastern Mills"
headline: "Southeastern Mills is creating best-in-business solutions for the food industry and showing them off with a best-in-business website."
agency:
 - "Erwin Penland"
 - "http://www.erwinpenland.com/"
liveUrl: https://sem-pro.com
technologies:
  - HTML
  - SCSS
  - Javascript / jQuery
  - AJAX
  - Twig Templating
  - Slim Framework
screenshots: true
logo: true
---

Southeastern Mills has a good thing going but their former website was truly holding them back. They needed an online space where they could shine and a small team at Erwin Penland came through.

<br />

The weeks leading up to development kickoff I was studying web performance. A performance budget sounded less like a trend and more like the right way to go about a project so I planned on following one on the next project I worked on. Turns out that the next project I worked on was pretty much already designed by the time I was told about it so I took what they gave me and set performance goals for myself, conidering competition and nature of the design. The design wasn't bad, I was just hoping to be able to bring up the budget in the planning and wireframing phase.The design is image-rich, including video hosted at Vimeo. I knew that would be a pain point performance-wise and poured a lot of attention into efficient assets (No div-itis, modular CSS, sprinklings of Javascript, etc.).

<br />

I ran web page tests on the two largest competitors and set my goals to have a 20% smaller homepage, lower speed index, and faster load.

<br />

Of course, as it turns out, once again, front-end work worth talking about is hard and adding performance consideration to the mix just takes it to another level. Every decision was important.

<br />

Given the nature of a site like this, and the amount of people that may end up working on it, and the likelihood that it would always be me, and the fact that there was no build-process, I decided to keep things pretty conventional. I compressed images, did a couple lazy-load tricks when Javascript is available, AJAxed hidden content in, and used SVG where I could.

<br />

![SE Mills performance Compared against competition and personal goals](/images/graphics/sem-performance.jpg)

<small>* Excluding a 28.8mb hero video...</small>

