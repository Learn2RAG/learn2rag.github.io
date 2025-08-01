---
title: "Events"
layout: single
permalink: /events/
---

## Nächste Events

<ul>
  {% assign now = site.time | date: "%Y-%m-%d" %}
  {% assign upcoming_events = site.events | where_exp: "item", "item.event_date" | sort: "event_date" %}
  {% for event in upcoming_events %}
    {% assign event_date_str = event.event_date | date: "%Y-%m-%d" %}
    {% if event_date_str >= now %}
      <li>
        <strong>{{ event.title }}</strong> — 
        {{ event.event_date | date: "%d.%m.%Y" }} — 
        <a href="{{ event.url }}">Mehr Info</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>

---

## Vergangene Events

<ul>
  {% assign past_events = site.events | where_exp: "item", "item.event_date" | sort: "event_date" | reverse %}
  {% for event in past_events %}
    {% assign event_date_str = event.event_date | date: "%Y-%m-%d" %}
    {% if event_date_str < now %}
      <li>
        <strong>{{ event.title }}</strong> — 
        {{ event.event_date | date: "%d.%m.%Y" }} — 
        <a href="{{ event.url }}">Mehr Info</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>
