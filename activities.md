---
layout: single
toc: true
title: "Activities"
permalink: /activities/
---

## Leadership

<ul>
{% for activity in site.data.activities %}
    {% if activity.type == "Leadership" %}
        <li>
            {{ activity.organization }} - {{ activity.title }}
        </li>
    {% endif %}
{% endfor %}
</ul>

## Teaching

<ul>
{% for activity in site.data.activities %}
    {% if activity.type == "Teaching" %}
        <li>
            {{ activity.organization }} - {{ activity.title }}
        </li>
    {% endif %}
{% endfor %}
</ul>

## Professional Development

<ul>
{% for activity in site.data.activities %}
    {% if activity.type == "Professional Development" %}
        <li>
            {{ activity.organization }} - {{ activity.title }}
        </li>
    {% endif %}
{% endfor %}
</ul>
