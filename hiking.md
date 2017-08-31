---
layout: page
permalink: /misc/hiking.html
title: Hiking and via ferratas


ferrata_wishlist:
    - name: Zittergrat
      location: Engelberg
      difficulty: K4
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/zittergrat/

    - name: Furenwand
      location: Engelberg
      difficulty: K4-K5
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/fuerenwand/

    - name: Graustock
      location: Engelberg
      difficulty: K3
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/graustock/

    - name: Rigidalstock
      location: Engelberg
      difficulty: K3
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/rigidalstock/

    - name: Krokodil
      location: Andermatt
      difficulty: K3-K4
      url: http://www.andermatt.ch/en/sommer/bergsteigen-klettern/Klettersteig-Bergsee

hiking_wishlist:

    - name: Four Headwaters 5 day
      location: Andermatt
      difficulty:
      url: http://www.andermatt.ch/en/summer/hiking/multi-day-tours/four-headwaters-trail2#skip

    - name: Sardona Heritage tour 6 day
      location:
      difficulty:
      url: http://www.wanderland.ch/en/routes/route-073.html

    - name: Alpnachstad-Pilatus Kulm
      location: Luzern
      difficulty:
      url:  https://www.pilatus.ch/fileadmin/files/entdecken/aktivitaeten/wandern-am-pilatus/1.1.1.3_Wandern_am_Pilatus_5.pdf

    - name: Santis
      location:
      difficulty: 1700m ascent/descent
      url: http://www.hikr.org/tour/post67759.html

    - name: Alpstein 3 lakes
      location:
      difficulty:
      url: http://www.appenzell.ch/en/alpstein/hiking/hiking-tour-suggestions/the-mountain-lakes-of-the-alpstein.html

    - name: Santis-Altmann ridge
      location:
      difficulty:
      url: https://www.myswitzerland.com/en-us/summer-weather-nodes/good_weather_summer/adventure-weather-summer/adventure-sports-summer/hiking-outdoor/panorama-trails/hiking-the-ridge-between-mts-saentis-and-altmann.html

    - name: Lauterbrunnen
      location: Lauterbrunnen
      difficulty:
      url:

---

### Hikes
{% for r in page.hikes %}
{{r.date}}: [{{r.name}}]({{r.url}}){% if r.location %}, *{{r.location}}* {% endif %}{% if r.difficulty %} ({{r.difficulty}}) {% endif %}{% if r.route %} [[GPS track]({{r.route}})]{% endif %}<br />{% endfor %}

### Via ferratas
{% for r in page.ferratas %}
{{r.date}}: [{{r.name}}]({{r.url}}){% if r.location %}, *{{r.location}}* {% endif %}{% if r.difficulty %} ({{r.difficulty}}) {% endif %}{% if r.route %} [[GPS track]({{r.route}})]{% endif %}<br />{% endfor %}

### Hiking wishlist
{% for r in page.hiking_wishlist %}
[{{r.name}}]({{r.url}}){% if r.location %}, *{{r.location}}* {% endif %}{% if r.difficulty %} ({{r.difficulty}}) {% endif %}<br />{% endfor %}


### Via ferrata wishlist
{% for r in page.ferrata_wishlist %}
[{{r.name}}]({{r.url}}){% if r.location %}, *{{r.location}}* {% endif %}{% if r.difficulty %} ({{r.difficulty}}) {% endif %}<br />{% endfor %}
