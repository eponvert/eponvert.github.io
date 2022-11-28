---
layout: page
title: This is the personal website of Elias Ponvert
---

Mostly some writings and stuff

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }})<br>{{ post.date | date_to_string }}
{% endfor %}

## Backstory

I am:
* a PhD in linguistics from The University of Texas
* a citizen of Austin, Texas since 2000
* husband of the extraordinary Candace Pruett
* father of four kids
* also two cats and a dog
* originally from Newport, Rhode Island
* formerly a citizen of Montreal, Quebec and student at McGill

## Elsewhere

* <a href="https://mastodon.social/@eponvert" rel="me">@eponvert@mastodon.social</a>
