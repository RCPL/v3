---
title: The Library
layout: default
breadcrumbs: ["The Library"]
---

<img src="/img/aerial.jpg">

Richland Library is the public library system of Richland County, South Carolina. In December 2012, the library shortened its name from Richland County Public Library. It has 11 branches including its 242,000 sq ft (22,500 m2) Main Library. In 2001, it was named the National Library of the Year by the Library Journal and the Gale Group.
## Library History
## Locations

<img class="full" src="/img/map-tour.png">

## Departments & Spaces
## Services
## Staff
a list of people who work for us

# Events
<ul>
  {% for event in site.events %}
    <li>
      <a href="{{event.url}}">{{event.title}}</a>
    </li>
  {% endfor %}
</ul>
