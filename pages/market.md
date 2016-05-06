---
layout: default
title: "Market Analysis"
teaser: ""
header:
   image_fullwidth: header-market3.jpg
permalink: "/market/"
---
<div id="blog-index" class="row">
	<div class="small-12 columns t30">

		<h1>{{ page.title }}</h1>
		{% if page.teaser %}<p class="teaser">{{ page.teaser }}</p>{% endif %}

<ul>
    {% for post in site.categories.market %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>


	</div><!-- /.small-12.columns -->
</div><!-- /.row -->