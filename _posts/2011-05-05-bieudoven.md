---
date: 2018-07-20 12:26:40
layout: post
title: Venn diagram
subtitle: Bài toán biểu đồ Ven
description: Có bạn nuôi chó, có bạn nuôi mèo, và có bạn nuôi cả hai con. Vậy chúng ta đang đếm bao nhiêu bạn?
image: https://res.cloudinary.com/dogipandt/image/upload/v1635742744/backgroun-Venn_hv8eei.png
optimized_image: https://res.cloudinary.com/dogipandt/image/upload/v1635742744/backgroun-Venn_hv8eei.png
category: logical
tags:
  - Venn diagram
  - set and subset
  - counting
  - intermediate
author: minhtrung
accordion:
  - title: Key notations
    content: <p> \(\cap \) = intersection <p> \(cup\) = union. <p> Given 2 sets A, B. then \(\mid A \mid \) is the number of elements in A, and \(\mid A \cap B \mid \) is the number of elements that belong to both A and B, and \(\mid A \cup B \mid \) is the number of elemnts in either A or B. <\p>
  - title: Key tools
    content: One of the key formula is \( \mid A \cup B \mid = \mid A \mid + \mid B \mid - \mid  A \cap B \mid \). It is easy to see that this equal to the number of elements that belong to A, and the number of element that belongs to B, minus those that belong to both sets (which were counted twice)
  - title: General theory
    content: <p> In general, the same proof can be applied to prove the more general case with n sets \(A_i\) for \(i \in \{1,2, \cdots ,n\} \), which states that \[\mid A \bigcup B \mid = \mid \bigcap_{i}A_i \mid - \mid \bigcap_{i,j}A_{i,j} \mid + \mid  \bigcap_{i,j,k}A_{i,j,k}\mid - \cdots \], and so on.
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
<a href="https://scratch.mit.edu/projects/566530728/fullscreen/"> Toggle fullscreen </a>
<iframe src="https://scratch.mit.edu/projects/566530728/embed" allowtransparency="true" width="485" height="402" frameborder="0" scrolling="no" allowfullscreen></iframe>





