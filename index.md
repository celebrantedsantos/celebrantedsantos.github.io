---
layout: default
language: pt-br
--- 
<div id="main">
	{% if page.language == "en" %}
	{% assign data = site.data.dataen %} 
	{% else %}
	{% assign data = site.data.data %} 
	{% endif %}  
	{% include celebrante.html %}	
	{% include casamentos.html %}
	{% include contact.html %}
</div>