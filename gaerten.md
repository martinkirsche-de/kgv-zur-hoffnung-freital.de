---
layout: default
title: "Gärten"
main_weight: 1
---

![Sparten Übersicht](assets/images/sparte-uebersicht.jpg)

So präsentieren sich die KGV "Volksgesundheit", "Zur Hoffnung" und "Sonneneck" (von links)



{% for garten in site.gaerten | sort: 'nummer' %}<img src="gaerten/{{ garten.nummer }}.jpg" alt="Garten Nummer {{ garten.nummer }}" style="float: none; width: 30%; margin: 0.3rem;">{% endfor %}
