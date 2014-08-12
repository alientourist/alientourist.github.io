---
title: alientourist
---
<!doctype html>
<html>

<head>
<meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="chrome=1">
<link rel="stylesheet" href="stylesheets/styles.css">
<link rel="stylesheet" href="stylesheets/pygment_trac.css">
<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">
<!--[if lt IE 9]>
<script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
<![endif]-->
</head>

<body>

<div class="wrapper">

<header>
<h1>alientourist.github.io</h1>
<p>The most important news.</p>
</header>

<section>
<ul>
  {% for post in site.posts limit: 5 %}
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
</section>

<footer>
<p><small>Hosted on GitHub Pages &mdash; Theme by <a href="https://github.com/orderedlist">orderedlist</a></small></p>
</footer>

</div>

<script src="javascripts/scale.fix.js"></script>
</body>
</html>
