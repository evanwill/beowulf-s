---
layout: page
title: Home
---
{%- assign items = site.data[site.metadata] -%}
<div class="row">
  <div class="col-md-8">

    {% include index/description.html %}
    

  </div>
  <div class="col-md-4">  

    {% include index/time.html %}

    {% include index/featured-terms.html field="language_display" title="Translation Language" btn-color="info" %}

    {% include index/featured-terms.html field="category" title="Category" btn-color="outline-secondary" %}
    
    {% include index/objects.html %}

  </div>
  <div class="col-md-12">

    {% include index/data-download.html %}

  </div>

</div>
