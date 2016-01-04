---
layout: post
title:  "Grid Experiments"
date:   2015-12-31 11:25:12 -0600
---

<h1 class="h1__rule">
  Flebox grid
</h1>
<p>
  An expriment in creating a flexbox grid. This is not something I would want to use in production yet - it is too limited and I haven't been able to figure out how to handle multiple sized grids (like the sm, md, and lg grid modifiers on the Bootstrap and Foundation grids).
</p>

<div class="grid grid__gutters grid__example">
  <div class="grid--cell grid--cell__2">
    <div class="grid--cell--content">
      <p>
        .grid--cell<br/>
        .grid--cell__2
      </p>
    </div>
  </div>
  <div class="grid--cell grid--cell__10">
    <div class="grid--cell--content">
      <p>
        .grid--cell<br/>
        .grid--cell__10
      </p>
    </div>
  </div>
</div>

<div class="grid grid__gutters grid__example">
  <div class="grid--cell grid--cell__6">
    <div class="grid--cell--content">
      <p>
        .grid--cell<br/>
        .grid--cell__6
      </p>
    </div>
  </div>
  <div class="grid--cell grid--cell__6">
    <div class="grid--cell--content">
      <p>
        .grid--cell<br/>
        .grid--cell__6
      </p>
    </div>
  </div>
</div>

<div class="grid grid__gutters grid__example">
  <div class="grid--cell grid--cell__4">
    <div class="grid--cell--content">
      <p>
        .grid--cell<br/>
        .grid--cell__4
      </p>
    </div>
  </div>
  <div class="grid--cell grid--cell__4">
    <div class="grid--cell--content">
      <p>
        .grid--cell<br/>
        .grid--cell__4
      </p>
    </div>
  </div>
  <div class="grid--cell grid--cell__4">
    <div class="grid--cell--content">
      <p>
        .grid--cell<br/>
        .grid--cell__4
      </p>
    </div>
  </div>
</div>

