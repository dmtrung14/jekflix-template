---
date: 2021-06-08 12:00:00
layout: post
title: Snow White and the Seven Dwarfs - Combination
subtitle: Nàng Bạch Tuyết và Bảy chú lùn - Toán tổ hợp
description: Bạch Tuyết đang có những ngày tháng vui vẻ với các chú lùn, nhưng làm thế nào để sắp xếp họ làm việc nhà đây?
category: counting
image: https://res.cloudinary.com/dogipandt/image/upload/v1635742744/combination_q8brh6.png
optimized_image: https://res.cloudinary.com/dogipandt/image/upload/v1635742744/combination_q8brh6.png
tags:
  - princess
  - intermediate
  - ordering
  - number of ways
author: minhtrung
accordion:
  - title: Combinatorics notations
    content: <p> 1. \(\binom{n}{k}\) = The number of ways to choose k elements out of n elements. In some books, you might also see \(C_{n}^k\). <p> 2. \(n! = n \times (n-1) \times (n-2) \times \cdots \times 1\)
  - title: Fomulas
    content: <p> The number of ways to order n elements on a row = \(n!\). <p> Similarly, we have \(n!\) ways to arrange elements on a circle, but because the circle can be rotated \(n\) times, the number of ways to order n elements on a circle is \[\frac{n!}{n} = (n-1)! \] The number of ways to select k out of n elements is \[\binom{n}{k}=\frac{n!}{k!(n-k)!}\] This is the \(\textbf{combination}\) of k elements, they don't bother order of selection. But \(\textbf{permutation}\) does. The permutation of k out of n elements is \[P_{n}^k=\frac{n!}{(n-k)!}\]Make sure not to confuse between the two notations. 
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
<a href= "https://scratch.mit.edu/projects/575168430/fullscreen/">Toggle fullscreen </a>
<iframe src="https://scratch.mit.edu/projects/575168430/embed" allowtransparency="true" width="970" height="804" frameborder="0" scrolling="no" allowfullscreen></iframe>