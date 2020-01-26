---
layout: collections
permalink: /art_movements/
---

<div class="row">

  {% for movement in site.art_movements %}
    
    <a href="{{ movement.url | prepend: site.baseurl }}">
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="panel panel-primary">
          <div class="panel-heading">
              {{ movement.title }}
          </div>
          <div class="panel-body">
            {{ movement.excerpt }}
          </div>
        </div>
      </div>
    </a>

  {% endfor %}

</div>
