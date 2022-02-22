---
layout: page
title: Case Studies
permalink: /case_studies/
---

# Case Studies for Teaching HCI Engineering

<div>
{% for cs in site.case_studies %}
    <div class="card">
      <div class="card-body">
        <h5 class="card-title"><a href="{{site.baseurl}}{{ cs.url }}">{{ cs.title}}</a></h5>
        <p class="card-text text-ellipsis--4">
            {{ cs.brief-description }}
        </p>
        <span class="card-subtitle mb-2 text-muted">
            <strong>Domains:</strong> {% for app in cs.application-domains %}
                <span class="badge bg-secondary">{{ app }}</span>
            {% endfor %}
        </span>
      </div>
    </div>
{% endfor %}
</div>
