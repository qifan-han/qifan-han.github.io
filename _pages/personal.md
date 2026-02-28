---
layout: archive
title: ""
permalink: /personal/
author_profile: true
---

<style>
  body {
    line-height: 1.4; /* Adjust line spacing */
  }

  p, li {
    font-size: 1em; /* Font size for regular text */
  }

  .coauthors, .subcontent {
    font-size: 0.9em; /* Customize specific classes if needed */
  }

  /* Only remove underline and set color for links within .main-content */
  .main-content a,
  .main-content a:link,
  .main-content a:visited,
  .main-content a:hover,
  .main-content a:active {
    color: #007bff !important;
    text-decoration: none !important;
  }

  .abstract {
    display: none; /* Hide the abstract by default */
    text-align: justify; /* Justify text for better readability */
    margin-top: 5px;
  }

  h2, h3 {
    margin-top: 1.5em; /* Increase space above headings */
  }

  /* Indent subcontents and add bullet points for them */
  ul.subcontent {
    list-style-type: circle; /* Set bullet points to circles for subcontent */
    margin-left: 10px; /* Indent subcontents */
    padding-left: 10px; /* Reduce padding for subcontent */
  }

  /* Divider between each paper */
  .underline {
    display: block;
    margin: 20px 0;
    border-bottom: 1px solid #ddd;
  }
</style>

<script>
  function toggleAbstract(id) {
    var abstract = document.getElementById(id);
    if (abstract.style.display === "none" || abstract.style.display === "") {
      abstract.style.display = "block";
    } else {
      abstract.style.display = "none";
    }
  }
</script>

<div class="main-content" markdown="1">

In my spare time, I enjoy watching soccer, tennis, and Formula 1 matches. I have been a fan of [Liverpool FC](https://www.liverpoolfc.com) since my childhood. During my studies at LSE in 2019, I decided to watch a Liverpool match and ended up choosing the semi-final second leg between Liverpool FC and Barcelona FC. It turned out to be the best live sports experience of my life, as Liverpool achieved a miraculous 4–0 comeback and went on to win the Champions League that year.

<p align="center">
  <img 
    src="/images/personal_photo.JPG" 
    alt="Liverpool Live" 
    title="My experience at Anfield" 
    width="400"
/>
</p>

<!--I also enjoy playing video games and often look for new research ideas in this market. My favorite genre is Japanese role-playing games, and I have been a fan of the [Pokémon](https://en.wikipedia.org/wiki/Pokémon) series since 2005. -->

<p>
  I also enjoy playing video games and often look for new research ideas in this market. My favorite genre is Japanese role-playing games, and I have been a fan of the <a href="https://en.wikipedia.org/wiki/Pokémon">Pokémon</a> series since 2005.
</p>

<p>
  Here is my 
  <a href="javascript:void(0);" onclick="toggleAbstract('goty_list')">
    Game of the Year list
  </a> 
  in recent years.
</p>

<div id="goty_list" class="abstract">
  <ul class="subcontent">
    <li><strong>2024:</strong> <a href="https://en.wikipedia.org/wiki/Black_Myth:_Wukong">Black Myth: Wukong</a>; <a href="https://en.wikipedia.org/wiki/Shin_Megami_Tensei_V">Shin Megami Tensei V: Vengeance</a></li>
    <li><strong>2025:</strong> <a href="https://en.wikipedia.org/wiki/Donkey_Kong_Bananza">Donkey Kong Bananza</a></li>
  </ul>
</div>



<!--My Game of the Year for 2024 is shared by [Black Myth: Wukong](https://en.wikipedia.org/wiki/Black_Myth:_Wukong) and [Shin Megami Tensei V: Vengeance](https://en.wikipedia.org/wiki/Shin_Megami_Tensei_V).-->

</div>
