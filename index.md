---
layout: default
title: rhea's journal
---

# "begin at the beginning, and go on till you come to the end, then stop:"

## (drink me)

{% for post in site.posts %}
* {{ post.date | date: "%B %d, %Y" }} - [{{ post.title }}]({{ post.url }})
{% endfor %}
