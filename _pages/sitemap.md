---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

A list of all the posts and pages found on the site. For you robots out there, there is an [XML version]({{ base_path }}/sitemap.xml) available for digesting as well.

<h2>Pages</h2>
{% for post in site.pages %}
{% if post.title and post.title != "" %}
{% unless post.sitemap == false or post.redirect_to %}
  {% include archive-single.html %}
{% endunless %}
{% endif %}
{% endfor %}

{% if site.posts.size > 0 %}
<h2>Posts</h2>
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}

{% for collection in site.collections %}
{% if collection.output and collection.docs.size > 0 and collection.label != "posts" %}
<h2>{{ collection.label }}</h2>
{% for post in collection.docs %}
  {% include archive-single.html %}
{% endfor %}
{% endif %}
{% endfor %}
