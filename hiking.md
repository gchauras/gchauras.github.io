---
layout: page
permalink: /misc/hiking.html
title: Hiking and via ferratas

hikes:
    - name: Lavertezzo-Cardada
      location: Ticino, Switzerland
      difficulty: 1800m, 14km, 7.5h
      url: https://map.wanderland.ch/?lang=de&route=all&bgLayer=pk&resolution=10&E=2705770&N=1120543&trackId=3874842&layers=Wanderland
      track: https://connect.garmin.com/modern/activity/1957616494
      date: 3 Sept 2017
      public_album:
      private_album:

    - name: Creux du Van
      location:
      difficulty:
      track: https://connect.garmin.com/modern/activity/1930666362
      date: 20 August 2017
      public_album:
      private_album:

    - name: Rigi Kulm
      location:
      difficulty:
      track: https://connect.garmin.com/modern/activity/1942609063
      date: 7 August 2017
      public_album:
      private_album:

    - name: Splugen
      location:
      difficulty:
      track: https://connect.garmin.com/modern/activity/1779988900
      date: 3 June 2017
      public_album:
      private_album:

    - name: Stoos
      location:
      difficulty:
      track: https://connect.garmin.com/modern/activity/1858515578
      date: 16 July 2017
      public_album:
      private_album:

    - name: Herbetswil
      location:
      difficulty:
      track: https://connect.garmin.com/modern/activity/1771314304
      date: 28 May 2017
      public_album:
      private_album:

    - name: Four Headwaters stage 1-2
      difficulty: 2 days
      location: Andermatt
      url: http://www.andermatt.ch/en/summer/hiking/multi-day-tours/four-headwaters-trail2#skip
      track:
        - https://connect.garmin.com/modern/activity/1388356183/2
        - https://connect.garmin.com/modern/activity/1388356232
      date: 1 October 2016
      public_album:
      private_album:


ferratas:
    - name: Tierbergli
      location: Gadmen
      difficulty: K2
      url: http://www.visinand.ch/via/Bern/Tierbergli/Tierbergli_intro.htm
      track: https://connect.garmin.com/modern/activity/1379235891
      date: 25 Sept 2016
      public_album:
      private_album:

    - name: Furenwand
      location: Engelberg
      difficulty: K4-K5
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/fuerenwand/
      track: https://connect.garmin.com/modern/activity/1325959012
      date: 28 August 2016
      public_album:
      private_album:


ferrata_wishlist:
    - name: Zittergrat
      location: Engelberg, Switzerland
      difficulty: K4
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/zittergrat/

    - name: Graustock
      location: Engelberg, Switzerland
      difficulty: K3
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/graustock/

    - name: Rigidalstock
      location: Engelberg, Switzerland
      difficulty: K3
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/rigidalstock/

    - name: Krokodil
      location: Andermatt, Switzerland
      difficulty: K3-K4
      url: http://www.andermatt.ch/en/sommer/bergsteigen-klettern/Klettersteig-Bergsee

    - name: Kandersteg
      location: Bernese Oberland
      difficulty: K4
      url: http://www.allmenalp.ch/aktivitaeten/klettersteig/?L=1

hiking_wishlist:

    - name: Mt. Blanc tour (xx days)
      location:
      difficulty:
      url:

    - name: Four Headwaters 5 day
      location: Andermatt, Switzerland
      difficulty:
      url: http://www.andermatt.ch/en/summer/hiking/multi-day-tours/four-headwaters-trail2#skip

    - name: Sardona Heritage tour 6 day
      location:
      difficulty:
      url: http://www.wanderland.ch/en/routes/route-073.html

    - name: Alpnachstad-Pilatus Kulm
      location: Luzern, Switzerland
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
      location: Lauterbrunnen, Switzerland
      difficulty:
      url:

---

### Hikes
{% for r in page.hikes %}
{% if r.date %}{{ r.date | date: "%-d %B %Y"  }}: {% endif %}[{{r.name}}]({{r.url}}){% if r.location %}, *{{r.location}}* {% endif %}{% if r.difficulty %} ({{r.difficulty}}){% endif %} [{% if r.track %}[GPS track]({{r.track}}){% endif %}{% if r.public_album %}, [public photos]({{r.public_album}}){% endif %}{% if r.private_album %}, [private photos]({{r.private_album}}){% endif %}]<br />{% endfor %}

### Via ferratas
{% for r in page.ferratas %}
{% if r.date %}{{ r.date | date: "%-d %B %Y"  }}: {% endif %}[{{r.name}}]({{r.url}}){% if r.location %}, *{{r.location}}* {% endif %}{% if r.difficulty %} ({{r.difficulty}}){% endif %} [{% if r.track %}[GPS track]({{r.track}}){% endif %}{% if r.public_album %}, [public photos]({{r.public_album}}){% endif %}{% if r.private_album %}, [private photos]({{r.private_album}}){% endif %}]<br />{% endfor %}

### Hiking wishlist
{% for r in page.hiking_wishlist %}
[{{r.name}}]({{r.url}}){% if r.location %}, *{{r.location}}* {% endif %}{% if r.difficulty %} ({{r.difficulty}}) {% endif %}<br />{% endfor %}

### Via ferrata wishlist
{% for r in page.ferrata_wishlist %}
[{{r.name}}]({{r.url}}){% if r.location %}, *{{r.location}}* {% endif %}{% if r.difficulty %} ({{r.difficulty}}) {% endif %}<br />{% endfor %}
