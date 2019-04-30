<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
    <title>{% if page.title %}{{ page.title }} | {% endif %}{{ site.title }}</title>
    <meta name="author" content="BieYuu" />
    <meta name="renderer" content="webkit">
    <meta name="description" content="BeiYuu's Blog" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, minimum-scale=1.0">
    <link rel="shortcut icon" href="/favicon.ico" type="image/x-icon" />
    <link rel="alternate" type="application/atom+xml" title="Recent Entries" href="{{ site.feed }}" />
    <style>{% include style.css %}</style>
  </head>

<body>
  <div class="index-wrapper">
    <div id="particles-js" style="background-image: url('');background-size: 20%;background-repeat: no-repeat;background-position: 80% 20%;"></div>
    <div class="aside">
      <div class="info-card">
        <h1>BeiYuu</h1>
        <a href="http://weibo.com/beiyuu/" target="_blank"><img src="http://www.weibo.com/favicon.ico" alt="" width="25"/></a>
        <a href="http://www.douban.com/people/beiyuu/" target="_blank"><img src="http://www.douban.com/favicon.ico" alt="" width="22"/></a>
        <a href="http://instagram.com/beiyuu/" target="_blank"><img src="http://d36xtkk24g8jdx.cloudfront.net/bluebar/00c6602/images/ico/favicon.ico" alt="" width="22"/></a>
      </div>
    </div>

    <div class="index-content">
      <ul class="artical-list">
        {% for post in site.categories.blog %}
        <li>
          <a href="{{ post.url }}" class="title">{{ post.title }}</a>
          <div class="title-desc">{{ post.description }}</div>
        </li>
        {% endfor %}
      </ul>
    </div>
  </div>
</body>
<script src="https://cdn.jsdelivr.net/npm/particles.js@2/particles.js"></script>
<script src="{{site.url}}{{site.baseurl}}/assets/js/particles_conf.js"></script>
</html>
