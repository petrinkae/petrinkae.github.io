---
layout: single
toc: true
title: "Activities"
permalink: /activities/
---

## Leadership

<div class="activities">
{% for activity in site.data.activities %}
    {% if activity.type == "Leadership" and activity.show_flag == "TRUE" %}
        <h3>{{ activity.title }}</h3>
        <h6>{{ activity.organization }} <em>{{ activity.start }} - {{ activity.end }}</em></h6>
    {% endif %}
{% endfor %}
</div>

## Teaching

<div class="activities">
{% for activity in site.data.activities %}
    {% if activity.type == "Teaching" and activity.show_flag == "TRUE" %}
        <h3>{{ activity.title }}</h3>
        <h6>{{ activity.organization }} <em>{{ activity.start }} {% if activity.end %} - {{ activity.end }} {% endif %}</em></h6>
    {% endif %}
{% endfor %}
</div>

## Professional Development

<div class="activities">
{% for activity in site.data.activities %}
    {% if activity.type == "Professional Development" and activity.show_flag == "TRUE" %}
        <h3>{{ activity.title }}</h3>
        <h6>{{ activity.organization }} <em>{{ activity.start }} {% if activity.end %} - {{ activity.end }} {% endif %}</em></h6>
    {% endif %}
{% endfor %}
</div>
