---
layout: single
toc: true
title: "Presentations, Workshops, & Publications"
permalink: /speaking/
---

## Workshops

<div class="activities">
{% for pub in site.data.pubs %}
    {% if pub.type == "Workshop" %}
        {% if pub.url %}
            <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h4>{{ pub.event }}</h4>
        <p><em>For {{pub.organization}} in {{ pub.year }}</em></p>
        <p>{{ pub.notes }}</p>
    {% endif %}
{% endfor %}
</div>

## Guides

<div class="activities">
{% for pub in site.data.pubs %}
    {% if pub.type == "Guide" %}
        {% if pub.url %}
            <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h4>{{ pub.event }}</h4>
        <p><em>For {{pub.organization}} in {{ pub.year }}</em></p>
        <p>{{ pub.notes }}</p>
    {% endif %}
{% endfor %}
</div>

## Presentations

<div class="activities">
{% for pub in site.data.pubs %}
    {% if pub.type == "Presentation" %}
        {% if pub.url %}
            <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h4>{{ pub.event }}</h4>
        <p><em>For {{pub.organization}} in {{ pub.year }}</em></p>
        <p>{{ pub.notes }}</p>
    {% endif %}
{% endfor %}
</div>

## Panels

<div class="activities">
{% for pub in site.data.pubs %}
    {% if pub.type == "Panel" %}
        {% if pub.url %}
            <h3><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
        {% else %}
            <h3>{{ pub.title }}</h3>
        {% endif %}
        <h4>{{ pub.event }}</h4>
        <p><em>For {{pub.organization}} in {{ pub.year }}</em></p>
        <p>{{ pub.notes }}</p>
    {% endif %}
{% endfor %}
</div>