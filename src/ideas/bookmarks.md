---
layout: layout.njk
title: Resources I Use
data: bookmarks
---
<h1 class="text-3xl font-bold text-gray-700 uppercase">{{title}}</h1>

<article class="my-6">
<h2 class="text-2xl font-bold text-yellow-800"> CSS</h2>
<ul>
{% for css in bookmarks %}
{% if css.tag == "css" %}
<li class="p-3 bg-gray-50"><a href="{{css.url}}" aria-label="{{css.aria}}">{{css.title}}</a><span class="text-sm pl-8"> By {{css.author}}</span> <span class="float-none md:float-right  text-xs p-1 bg-yellow-400" aria-label="{{css.title}} is also in the category of {{css.secondtag}}">{{css.secondtag}}</li>
{% else %}
{% endif %}
{% endfor %}
</ul> 
</article> 

<article class="my-6">
<h2 class="text-2xl font-bold text-yellow-800"> HTML</h2>
<ul>
{% for html in bookmarks %}
{% if html.tag == "html" %}
<li class="bg-gray-50 p-3"><a href="{{html.url}}" aria-label="{{html.aria}}">{{html.title}}</a><span class="text-sm pl-8"> By {{html.author}}</span> <span class="float-none md:float-right text-xs p-1 bg-yellow-400" aria-label="{{html.title}} is also in the category of {{html.secondtag}}">{{html.secondtag}}</span></li> 
{% else %}
{% endif %}
{% endfor %}
</ul>
</article>

<article class="my-6">
<h2 class="text-2xl font-bold text-yellow-800"> Accessibility</h2>
<ul>
{% for access in bookmarks %}
{% if access.tag == "accessibility" %}
<li class="bg-gray-50 p-3"><a href="{{access.url}}" aria-label="{{access.aria}}">{{access.title}}</a><span class="text-sm pl-8"> By {{access.author}}</span> <span class="float-none md:float-right text-xs p-1 bg-yellow-400" aria-label="{{access.title}} is also in the category of {{access.secondtag}}">{{access.secondtag}}</span></li> 
{% else %}
{% endif %}
{% endfor %}
</ul>
</article>