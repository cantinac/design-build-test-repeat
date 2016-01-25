---
layout: page
title: Episodes 
permalink: /episodes/
---

<ul class="episode-list">
  {% for episode in site.episodes %}
  <li class="episode">
    <header class="episode-header">
      <h2>
        <a class="episode-link" href="{{ episode.url | prepend: site.baseurl }}">{{ episode.title }}</a>
      </h2>
      <p class="episode-meta">{{ episode.date | date: "%b %-d, %Y" }}</p>
    </header>

    <article class="episode-summary" data-episode-prefix="In This Episode: ">
      {{ episode.summary }}
    </article>
  </li>
  {% endfor %}
</ul>