---
layout: default
title : Partenaires
---
<style>
  /*https://css-tricks.com/a-grid-of-logos-in-squares/*/
  .grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
    grid-gap: 1rem;
  }
  .grid > div {
    /*background: black;*/
    padding: 1rem;
    display: grid;
  }
  .grid > div::before {
    content: "";
    padding-bottom: 100%;
    display: block;
  }
  .grid > div::before,
  .grid > div > img {
    grid-area: 1 / 1 / 2 / 2;
  }
  .grid > div > img {
    width: 100%;
    height: 100%;
    object-fit: contain;
  }
</style>

<div class="grid">
  <div><img class="partenaire" src = "/assets/images/uqtr.jpg"/></div>
  <div><img class="partenaire" src = "/assets/images/rive.png"/></div>
</div>


