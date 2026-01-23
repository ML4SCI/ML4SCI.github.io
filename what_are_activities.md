---
title: "What are activity areas?"
author: "Graeme Stewart"
layout: default
---

# Activity Areas and Interest Groups

ML4SCI Activity Areas and Interest Groups are led by enthusiasts and
advocates for a particular area of work or of technology
interest and provide a focal point for organising discussions
in the HEP community. They can also cover engagement with
external projects, like Google's Summer of Code.

They are less formal, in ML4SCI, than [working groups](/what_are_WGs.html)
and any relevant and reasonable activity for HEP can spawn
an interest group. If you want to put some community-wide
activity under the umbrella of ML4SCI as an activity area or interest group
just contact the
[ML4SCI coordination team](mailto:ml4-sci@cern.ch).

Activity areas are added to the ML4SCI website, with 
description and contact information and will have a dedicated mailing list
and, if appropriate, an Indico category.

<ul class="list">
{% for activity in site.activities %}
  <li> <a href="{{ activity.url }}">{{ activity.title }}</a></li>
{% endfor %}
</ul>
