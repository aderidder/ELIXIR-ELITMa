---
title: Modules
---

{% for module in site.data.modules %}
  <div class="module">
    <h2>{{ module.title }}</h2>
    <p>{{ module.description }}</p>
    <p><strong>Learning objectives:</strong></p>
    <ul>
      {% for objective in module.objectives %}
        <li>{{ objective }}</li>
      {% endfor %}
    </ul>
    <p><strong>Delivery:</strong> {{ module.delivery }}</p>
    <p><strong>Course leads:</strong> {{ module.leads }}</p>
  </div>
{% endfor %}

