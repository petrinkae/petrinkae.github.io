---
layout: single
toc: true
title: "Workshops, Presentations & Panels"
permalink: /speaking/
---

## Workshops

<div class="activities">
{% for pub in site.data.speaking %}
    {% if pub.type == "Workshop" and pub.show_flag == "TRUE" %}
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
    {% if pub.type == "Presentation" and pub.show_flag == "TRUE" %}
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
    {% if pub.type == "Panel" and pub.show_flag == "TRUE" %}
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

## For the TJA

<div class="activities">
{% for pub in site.data.speaking %}
    {% if pub.type == "TJA" and pub.show_flag == "TRUE" %}
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

## Moderation

<div class="activities">
{% for pub in site.data.speaking %}
    {% if pub.type == "Moderation" and pub.show_flag == "TRUE" %}
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