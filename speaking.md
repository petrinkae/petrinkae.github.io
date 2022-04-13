---
layout: single
toc: true
title: "Workshops, Presentations & Panels"
permalink: /speaking/
---

## Workshops

<div class="activities">
{% for pub in site.data.speaking %}
    {% if pub.type == "Workshop" %}
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

## Presentations

<div class="activities">
{% for pub in site.data.speaking %}
    {% if pub.type == "Presentation" %}
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

## Panels

<div class="activities">
{% for pub in site.data.speaking %}
    {% if pub.type == "Panel" %}
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