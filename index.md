---
title: Geometry
layout: default
---

#Geometry

- - -

<div class="row">
	<div class="col-sm-3">
		<h4><span class="label label-info">Shapes</span></h4>
		<ol class="post-list">
 			{% for post in site.categories.shapes %}
   				<li><a href="{{ post.url }}">{{ post.postTitle }}</a></li>
 			{% endfor %}
		</ol>			
	</div>

	<div class="col-sm-3">
		<h4><span class="label label-info"></span></h4>
		<ol class="post-list">
 			{% for post in site.categories.basicoperators %}
   				<li><a href="{{ post.url }}">{{ post.postTitle }}</a></li>
 			{% endfor %}
		</ol>			
	</div>

	<div class="col-sm-3">
		<h4><span class="label label-info"></span></h4>
		<ol class="post-list">
 			{% for post in site.categories.strings_characters %}
   				<li><a href="{{ post.url }}">{{ post.postTitle }}</a></li>
 			{% endfor %}
		</ol>			
	</div>

	<div class="col-sm-3">
		<h4><span class="label label-info"></span></h4>
		<ol class="post-list">
 			{% for post in site.categories.collection_types %}
   				<li><a href="{{ post.url }}">{{ post.postTitle }}</a></li>
 			{% endfor %}
		</ol>			
	</div>

</div>

