---
layout: default
title: IceSky's blog
---

<div class="home">

  <ul class="posts">
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      
      <!--<div class="continue">
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </div>-->
    </li>
    {% endfor %}
  </ul>

</div>
