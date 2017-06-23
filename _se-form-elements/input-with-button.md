---
layout: default
title: Input with button 
usage: ..
---

<div class="input-group">
  <input type="text" class="form-control" placeholder="placeholder" aria-describedby="basic-addon2">
  <span class="input-group-addon" id="basic-addon2">button text</span>
</div>


<div class="search-box">
    <form class="search-box__form" method="GET" action="/search/">
        <label class="search-box__label hidden" for="search-box">Search</label>
        <input name="q" required="" id="search-box" class="search-box__input" type="text" placeholder="Search mygov.scot" autocomplete="off">

        <button type="submit" title="search" class="search-box__button primary">
            <img alt="" class="search-box__icon" src="/assets/images/icons/search-white_@2x.png">
            <span class="hidden">Search mygov.scot</span>
        </button>
    </form>
</div>