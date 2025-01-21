---
layout: default
language: en
locale: en
author: 'Diego Santos'
title:  'Celebrant Diego Santos'
description:  Celebrate your wedding with God's blessing, uniting faith and love!
site_name:  'Celebrant Diego Santos'
---
<div id="main"> {% if page.language == "en" %} {% assign data = site.data.dataen %}{% else %} {% assign data = site.data.data %} {% endif %}  
{% include celebrante.html %}	
{% include casamentos.html %}
{% include contact.html %}
</div>