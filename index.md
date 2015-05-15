---
layout: page
title: 江上的blog
---

{% include JB/setup %}

江上日出
I'm Here！
Follow me on [Twitter ←](https://twitter.com/jsrc001)
关注我的[微博 ←](http://weibo.com/jsrc)

## Blog Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


才不会告诉你我模版是抄某人的呢，o(￣ヘ￣o＃) 

