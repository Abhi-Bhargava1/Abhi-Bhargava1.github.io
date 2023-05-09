---
layout: page
permalink: /teaching/
title: misc. 
description: Here are some pictures from this past year. 
nav: true
nav_order: 5
---

<div class="grid-container">
  <div class="grid-item">
    <img src="/assets/img/misc_1.jpg" alt="Image 1">
    <p>description 1</p>
  </div>
  <div class="grid-item">
    <img src="/assets/img/misc_2.jpg" alt="Image 2">
    <p>description 1</p>
  </div>
  <div class="grid-item">
    <img src="/assets/img/misc_3.jpg" alt="Image 3">
    <p>description 1</p>
  </div>
  <div class="grid-item">
    <img src="/assets/img/misc_4.jpg" alt="Image 4">
    <p>description 1</p>
  </div>
    <div class="grid-item">
    <img src="/assets/img/misc_5.jpg" alt="Image 3">
    <p>description 1</p>
  </div>
  <div class="grid-item">
    <img src="/assets/img/misc_6.jpg" alt="Image 6">
    <p>description 1</p>
  </div>
</div>

## More to come ...


<style>
  .grid-container {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-gap: 20px;
  }
  .grid-item {
    position: relative;
  }
  .grid-item img {
    width: 100%;
    height: auto;
  }
  .grid-item p {
    text-align: center;
    margin-top: 5px;
    margin-bottom: 0;
    font-size: 14px;
  }
</style>
