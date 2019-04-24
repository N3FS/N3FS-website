---
layout: page
title: Help and Support
short_title: Help

data:
- title: Help and Guidelines
  docs:
    - link: /rules
- title: Policies and Forms
  docs:
    - link: /help/claims
    - link: /help/builder
    - link: /help/ban-appeal
    - link: /help/staff-application
- title: Contact
  docs:
    - link: /help/contact
---

{% for section in page.data %}
## {{ section.title }}

{% for item in section.docs %}
{% assign p = site.documents | where: "url", item.link | first %}
{% if p == null %}
{% assign p = site.pages | where: "url", item.link | first %}
{% endif %}

<a href="{{p.url}}" class="action">{{p.title}}</a>

{% endfor %}
{% endfor %}