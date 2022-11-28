---
layout: page
title: This is the personal website of Elias Franchot Ponvert
---

Mostly some writings and stuff

{% for post in site.posts %}
[{{ post.title }}]({{ post.url }})<br>{{ post.date | date_to_string }}
{% endfor %}

## Backstory

I am a PhD in linguistics from The University of Texas and BA from McGill;
I've been been in and around Austin, Texas since 2000; a father of four kids,
also a dog and some other animals; originally from Newport, RI and 
formerly lived in Montréal, Québec. Salut!

## Elsewhere

* <a href="https://mastodon.social/@eponvert" rel="me">@eponvert@mastodon.social</a>
