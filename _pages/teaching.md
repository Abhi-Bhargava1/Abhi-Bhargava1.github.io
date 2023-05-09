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
    <img src="/assets/img/1.jpg" alt="caption 1">
    <div class="caption">caption 1</div>
  </div>
  <div class="grid-item">
    <img src="/assets/img/2.jpg" alt="caption 2">
    <div class="caption">caption 2</div>
  </div>
  <div class="grid-item">
    <img src="/assets/img/3.jpg" alt="caption 3">
    <div class="caption">caption 3</div>
  </div>
  <div class="grid-item">
    <img src="/assets/img/4.jpg" alt="caption 4">
    <div class="caption">caption 4</div>
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
  .caption {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.5);
    color: white;
    text-align: center;
    padding: 5px;
  }
</style>
