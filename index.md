---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
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

