---
layout: "page"
title: Game Development
permalink: "/game-dev-blog"
---
start of game dev blog

{% for post in site.posts %}

	<li><a href="{{post.url}}">{{post.title}}</a></li>

{% endfor%}