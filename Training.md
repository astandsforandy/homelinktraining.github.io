---
layout: page
title: Schedule
permalink: /Schedule/
list_catagory: Training
---

HomeLink Home Care provides in depth training programs for full spectrum home care. Our programs are managed and ran by qualified and experienced nurses, not computer simulations like other education programs. The Home Health field is growing fast, set yourself apart in the field by taking our certified training program. Check out the upcoming sessions and contact us today to reserve a spot!

<div class="Programs">

  <h1>Upcoming Classes:</h1>

  <iframe src="https://www.google.com/calendar/embed?height=600&amp;wkst=1&amp;bgcolor=%23ff6600&amp;src=en.usa%23holiday%40group.v.calendar.google.com&amp;color=%232952A3&amp;ctz=America%2FNew_York" style=" border-width:0 " width="750" height="600" frameborder="0" scrolling="no"></iframe>

  <ul class="posts">
    {% for post in site.posts %}
      <li>
        <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>