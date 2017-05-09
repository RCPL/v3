---
title: Stories
layout: page
---

# All Stories
{% for story in site.stories %}
  <li>
    <a href="{{story.url}}">
			{{story.image}}
			{{story.title}}
		</a>
    {{story.excerpt}}
  </li>
{% endfor %}
