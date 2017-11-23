---
layout:  home
title: Home
---

<html>
<head>
	<title>{{site.name}}</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
</head>

<body>
<section id="bgimage">
	<div class="container">
			<ul>
			  {% for post in site.posts %}
			  <li>
			<span>{{ post.date | date: "%B %e, %Y" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
			  </li>
			  {% endfor %}
			</ul>
	</div>
</section>

<section id="divider">
	<h1> </h1>
</section>
</body>
</html>

