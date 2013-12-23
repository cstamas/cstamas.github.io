---
layout: page
title: Welcome
tagline: The new Minimalistic Blog Factory
---

This is my private page for blog and other "static" content. Feel free to peek around.

## About me

In short: OSS freak. Proximity, Nexus, Maven... Java OSS development for developers.

Am developer of Nexus at Sonatype (creator of Proximity, Nexus predecessor), with over 15 years of experience developing software systems in Public Services, Telco and Publishing industries. Am OSS enthusiast, committer on multiple OSS projects, over at Github, Apache, Codehaus and Source Forge. I gained visibility in Maven Community in 2005. with Proximity, which was the most advanced Maven Proxy at the time. Am one of the first hungarian adopters of "ice breaking" OSS technologies in commercial projects, like Spring and Maven are.

## Resources

* [Twitter](https://twitter.com/cstamas)
* [LinkedIn profile](http://www.linkedin.com/in/cservenak)
* [Ohloh profile](https://www.ohloh.net/accounts/cstamas)
* [Old blog](http://blogs.cservenak.com/)

## Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

