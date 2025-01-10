---
layout: single
toc: true
title: "Publications"
permalink: /writing/
---

## Documentation

<div class="activities">
{% for pub in site.data.combined %}
    {% if pub.type == "Documentation" and pub.show_flag == "TRUE" %}
        {% if pub.url %}
            <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h4>{{ pub.event }}</h4>
        <h6><em>For {{pub.organization}} in {{ pub.start_date }}</em></h6>
        <p>{{ pub.notes }}</p>
    {% endif %}
{% endfor %}
</div>

## Best Practices

<div class="activities">
{% for pub in site.data.combined %}
    {% if pub.type == "Best Practices" and pub.show_flag == "TRUE" %}
        {% if pub.url %}
            <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h4>{{ pub.event }}</h4>
        <h6><em>For {{pub.organization}} in {{ pub.start_date }}</em></h6>
        <p>{{ pub.notes }}</p>
    {% endif %}
{% endfor %}
</div>

## Guides

<div class="activities">
{% for pub in site.data.combined %}
    {% if pub.type == "Guide" and pub.show_flag == "TRUE" %}
        {% if pub.url %}
            <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h4>{{ pub.event }}</h4>
        <h6><em>For {{pub.organization}} in {{ pub.start_date }}</em></h6>
        <p>{{ pub.notes }}</p>
    {% endif %}
{% endfor %}
</div>