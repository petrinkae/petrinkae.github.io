---
layout: single
toc: true
title: "Publications"
permalink: /writing/
---

## Guides

<div class="activities">
{% for pub in site.data.writing %}
    {% if pub.type == "Guide" %}
        {% if pub.url %}
            <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h4>{{ pub.event }}</h4>
        <h6><em>For {{pub.organization}} in {{ pub.year }}</em></h6>
        <p>{{ pub.notes }}</p>
    {% endif %}
{% endfor %}
</div>

## Documentation

<div class="activities">
{% for pub in site.data.writing %}
    {% if pub.type == "Documentation" %}
        {% if pub.url %}
            <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h4>{{ pub.event }}</h4>
        <h6><em>For {{pub.organization}} in {{ pub.year }}</em></h6>
        <p>{{ pub.notes }}</p>
    {% endif %}
{% endfor %}
</div>