---
title: "What are working groups?"
author: "Graeme Stewart"
layout: default
---

# Working Groups

ML4SCI Working Groups are community led groups that organise activities
in particular domains with the aims of increading communication
between developers, providing a platform for discussion of interesting
problems and novel solutions developments, and fostering the adoption
of common software between different communities.

Working groups have three convenors, to help share the workload, and
are appointed by ML4SCI (via an open nomination process and a search
committtee) to serve for one year, with renewal possible by mutual
agreement. (Interest groups and activity areas are less formal.)

If you want to form a working group, or want to put some community-wide
activity under the umbrella of ML4SCI,
just contact the
[ML4SCI coordination team](mailto:ml4-sci@cern.ch).

Working Groups are added to the ML4SCI website, with 
description and contact information and will have a dedicated mailing list
and Indico category.

<ul class="list">
{% for wg in site.workinggroups %}
  <li> <a href="{{ wg.url }}">{{ wg.title }}</a></li>
{% endfor %}
</ul>
