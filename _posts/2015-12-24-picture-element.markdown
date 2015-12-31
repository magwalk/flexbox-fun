---
layout: post-blank
title:  "Picture Element"
date:   2015-12-24 11:25:12 -0600
categories: jekyll update
---
<div class="wrapper">
  <div class="wrapper--content">
    <h1 class="h1__rule">
      Playing with the responsive images!
    </h1>
    <h2 class="h2__uc">
      Large Image as background
    </h2>
    <p>
      The following hero image uses a 1280px x 400px background image at all screen sizes:
    </p>
  </div>
</div>

<div class="hero hero__customers picture-page"></div>

<div class="wrapper">
  <div class="wrapper--content">
    <h2 class="h2__uc">
      Different size background images - via CSS
    </h2>
    <p>
      The following hero image serves different background images via CSS media queries depending on the size of the screen.
      <ul>
        <li><strong>LARGE</strong> (greater than 1000px): 1280 x 400px</li>
        <li><strong>MEDIUM</strong> (less than 1000px and greater than 600px): 800 x 300px</li>
        <li><strong>SMALL</strong> (less than 600px): 600 x 350px</li>
      </ul>
    </p>
  </div>
</div>

<div class="hero hero__customers__responsive picture-page"></div>

<div class="wrapper">
  <div class="wrapper--content">
    <h2 class="h2__uc">
      Picture element
    </h2>
    <p>
      The following hero image serves different background images via CSS media queries depending on the size of the screen.
    </p>
  </div>
</div>

<div class="hero__picture">
  <picture>
    <source media="(min-width: 1000px)"
      srcset="{{ site.baseurl }}/images/customers/hero.png">
    <source media="(max-width: 1000px) and (min-width: 600px)"
      srcset="{{ site.baseurl }}/images/customers/hero-medium.png">
    <source media="(max-width: 600px)"
      srcset="{{ site.baseurl }}/images/customers/hero-small.png">
    <img src="{{ site.baseurl }}/images/customers/hero.png">
  </picture>
</div>