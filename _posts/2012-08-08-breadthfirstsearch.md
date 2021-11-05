---
date: 2018-02-03 12:26:40
layout: post
title: Breadth first search
subtitle: Tìm kiếm them chiều ngang.
description: Con đường nào rồi cũng dẫn đến thành Rome, nhưng  con đường nào  ngắn nhất và ít nguy hiểm nhất? Hãy tìm hiểu BFS nhé!
image: https://res.cloudinary.com/dogipandt/image/upload/v1635742743/tim-kiem-theo-chieu-rong_oqm1zw.png
optimized_image: https://res.cloudinary.com/dogipandt/image/upload/v1635742743/tim-kiem-theo-chieu-rong_oqm1zw.png
category: algorithms
tags:
  - breadth first search
  - BFS
  - santa claus
  - shortest route
  - difficult
author: minhtrung
accordion:
  - title: Theory
    content: <p> The nature of the BFS theorem is actually recursive deduction. <p> Assume we have a checkerboard, on which there is a chess piece, and the piece can jump between the squares. Denote the degree of piece's initial square as 0. Then, the degree \(n+1\) squares are those which the piece can jump directly to if it was standing on a degree \(n\) square. 
  - title: Key notices
    content: <p> 1. The difference between the degree of 2 adjacent square is \(1\). <p> 2. Remember only use this algorithm for moves that go further from the initial square. In other words, do not jump back to a numbered tile! 
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
<a href= "https://scratch.mit.edu/projects/566512570/fullscreen/">Toggle fullscreen </a>
<iframe src="https://scratch.mit.edu/projects/566512570/embed" allowtransparency="true" width="970" height="804" frameborder="0" scrolling="no" allowfullscreen></iframe>









