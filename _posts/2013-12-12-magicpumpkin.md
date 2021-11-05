---
date: 2017-07-29 13:24:49
layout: post
title: Magic Pumpkin - The 'singular' algorithm
description: Quả bí ngô kì diệu - thuật toán đơn độc
subtitle: Bà phù thủy có những chiếc đèn lồng bí ngô rất đẹp và cũng hoạt động rất khác thường. Làm sao bật hết các đèn lên đây?
image: https://res.cloudinary.com/dogipandt/image/upload/v1635742743/magic-pumkins_hzblxf.png
optimized_image: https://res.cloudinary.com/dogipandt/image/upload/v1635742743/magic-pumkins_hzblxf.png
category: challenges
tags:
  - difficult
  - algorithm
  - singular
  - optimal
author: minhtrung
accordion:
  - title: Theory
    content: <p> This is one of the more advanced problem. I call this the absolute singular problem. <p> The reason is, you can try multiple times and light up all 7 pumpkins. But what if the Witch has an enormous number of lamps, let's say, 2020? <p> She will probably need a computer to automatically turn on all the lights in a scripted and certain algorithm. And I say, she can change the status (on/off) of each individual lamp without changing the status of ANY other lamp. This you may try to prove true for all number of lamps not divisible by 3. <p> That is why I call this type of problem "singular", because every variable has an independent status, no matter if the other lamps are on/off.
  - title: How to brainstorm
    content: <p> I would say it's not difficult to prove this, but how do we come up with changing the status of each lamp? After all, this is a STRONGER problem than the original one. There are two signals for this <p> 1. All the variables are symmetric. In the case of this problem, all lamps are connected to two others, and lie on a circle, which makes them symmetric in terms of position. <p> 2. The initial/ending position are random. This means any transformation can happen right? And if so, why cannot we change the status of only one variable?
---
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>MathJax example</title>
  <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
  <script id="MathJax-script" async
          src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
  </script>
</head>
{% include accordion.html %}
<a href= "https://scratch.mit.edu/projects/566389290/fullscreen/">Toggle fullscreen </a>
<iframe src="https://scratch.mit.edu/projects/566389290/embed" allowtransparency="true" width="970" height="804" frameborder="0" scrolling="no" allowfullscreen></iframe>