---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

<head>
	<title>{{site.name}}</title>
	<link rel="stylesheet" type="text/css" href="css/style.css">
</head>


<div class="content">
  <div class="related">
    <ul>
      {% for post in site.posts %}
      <li>
	<span>{{ post.date | date: "%B %e, %Y" }}</span> <a href="{{ post.url }}">{{ post.title }}</a>
      </li>
      {% endfor %}
    </ul>
  </div>
</div>

<section id="showcase">
	<div class="container">
		<h1> .
		</h1>
	</div>
	


