---
date: 2018-04-21 12:26:40
layout: post
title: Prime detective
subtitle: Thám tử số nguyên tố
description: Có cách nào để "chỉ điểm" cho thám tử các số nguyên tố không?
image: https://res.cloudinary.com/dogipandt/image/upload/v1635742744/prime-number_afe8xw.png
optimized_image: https://res.cloudinary.com/dogipandt/image/upload/v1635742744/prime-number_afe8xw.png
category: algebra
tags:
  - prime numbers
  - algorithms
  - prime factorization
  - easy
author: minhtrung
accordion:
  - title: Theory
    content: Prime numbers are numbers that have only 2 factors, namely 1 and themselves.
  - title: Prime factorizing a number
    content: <p> It would be great if we can test all numbers from 1 to the number \(n\) itself, but that would be unnecessary. In order to know if a number is a prime or not, we only have to test all the prime numbers from 2 to \( \sqrt{n}\). <p> The reason is that, \(n\) cannot have 2 prime factors \(p,q\) greater than \(\sqrt{n}\), other wise, \(n=pq > \sqrt(n)^2), a contradiction. Therefore, if \(n\) is not a prime number, then it has at least one prime factor less than \(\sqrt{n}\)
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
<p> When \(a \ne 0\), there are two solutions to \(ax^2 + bx + c = 0\) and they are \[x = {-b \pm \sqrt{b^2-4ac} \over 2a}.\]</p>
{% include accordion.html %}
<a href="https://scratch.mit.edu/projects/566529696/fullscreen/">Toggle fullscreen </a>
<iframe src="https://scratch.mit.edu/projects/566529696/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>