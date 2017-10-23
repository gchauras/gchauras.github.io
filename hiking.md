---
layout: page
permalink: /misc/hiking.html
title: Hikes and via ferratas

completed:
    - name: Grossen Mythen
      location: Schwyz, Switzerland
      notes: 1400m, 6km, 2:45h
      url: http://www.schweizmobil.ch/de/wanderland/routen/route-0829.html
      track: https://connect.garmin.com/modern/activity/2161379113
      date: 21 Oct 2017
      photos:
      private_photos:

    - name: IGL Compass (incomplete)
      location: Preda-Bergun, Switzerland
      notes: 1200m, 14km
      url: https://map.schweizmobil.ch/?lang=en&trackId=3348194&land=wanderland&route=all&layers=Wanderwegnetz
      track: https://connect.garmin.com/modern/activity/2117617190
      date: 15 Oct 2017
      photos:
      private_photos:

    - name: Monte Bar
      location: Ticino, Switzerland
      notes: 1480+860 m, 11+16 km, 2 days
      url: https://map.wanderland.ch/?lang=de&route=all&bgLayer=pk&resolution=10&E=2705770&N=1120543&trackId=3874842&layers=Wanderland
      track:
        - https://connect.garmin.com/modern/activity/1985512528
        - https://connect.garmin.com/modern/activity/1985512490
      date: 17 Sept 2017
      photos:
      private_photos:

    - name: Lavertezzo-Cardada
      location: Ticino, Switzerland
      notes: 1800m, 14km, 7.5h
      url: https://map.wanderland.ch/?lang=de&route=all&bgLayer=pk&resolution=10&E=2705770&N=1120543&trackId=3874842&layers=Wanderland
      track: https://connect.garmin.com/modern/activity/1957616494
      date: 3 Sept 2017
      photos:
      private_photos:

    - name: Creux du Van
      location: Neuchatel, Switzerland
      url:
      notes: 800m
      track: https://connect.garmin.com/modern/activity/1930666362
      date: 20 August 2017
      photos:
      private_photos:

    - name: Rigi Kulm
      location: Luzern, Switzerland
      url:
      notes:
      track: https://connect.garmin.com/modern/activity/1942609063
      date: 7 August 2017
      photos:
      private_photos:

    - name: Splugen
      location:
      url:
      notes:
      track: https://connect.garmin.com/modern/activity/1779988900
      date: 3 June 2017
      photos:
      private_photos:

    - name: Stoos
      location:
      url:
      notes:
      track: https://connect.garmin.com/modern/activity/1858515578
      date: 16 July 2017
      photos:
      private_photos:

    - name: Herbetswil
      location:
      url:
      notes:
      track: https://connect.garmin.com/modern/activity/1771314304
      date: 28 May 2017
      photos:
      private_photos:

    - name: Four Headwaters stage 1-2
      notes: 2 days
      location: Andermatt, Switzerland
      url: http://www.andermatt.ch/en/summer/hiking/multi-day-tours/four-headwaters-trail2#skip
      track:
        - https://connect.garmin.com/modern/activity/1388356183/2
        - https://connect.garmin.com/modern/activity/1388356232
      date: 1 October 2016
      photos:
      private_photos:

    - name: Tierbergli via ferrata
      location: Gadmen, Switzerland
      notes: K2
      url: http://www.visinand.ch/via/Bern/Tierbergli/Tierbergli_intro.htm
      track: https://connect.garmin.com/modern/activity/1379235891
      date: 25 Sept 2016
      photos:
      private_photos:

    - name: Furenwand via ferrata
      location: Engelberg, Switzerland
      notes: K4-K5
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/fuerenwand/
      track: https://connect.garmin.com/modern/activity/1325959012
      date: 28 August 2016
      photos:
      private_photos:


wishlist:

    - name: Zittergrat via ferrata
      location: Engelberg, Switzerland
      notes: K4
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/zittergrat/

    - name: Graustock via ferrata
      location: Engelberg, Switzerland
      notes: K3
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/graustock/

    - name: Rigidalstock via ferrata
      location: Engelberg, Switzerland
      notes: K3
      url: http://www.engelberg.ch/en/sommer-in-engelberg/via-ferratas/rigidalstock/

    - name: Krokodil via ferrata
      location: Andermatt, Switzerland
      notes: K3-K4
      url: http://www.andermatt.ch/en/sommer/bergsteigen-klettern/Klettersteig-Bergsee

    - name: Kandersteg via ferrata
      location: Bernese Oberland
      notes: K4
      url: http://www.allmenalp.ch/aktivitaeten/klettersteig/?L=1

    - name: Mt. Blanc tour (xx days)
      location:
      notes:
      url:

    - name: Four Headwaters 5 day
      location: Andermatt, Switzerland
      notes:
      url: http://www.andermatt.ch/en/summer/hiking/multi-day-tours/four-headwaters-trail2#skip

    - name: Sardona Heritage tour 6 day
      location:
      notes:
      url: http://www.wanderland.ch/en/routes/route-073.html

    - name: Alpnachstad-Pilatus Kulm
      location: Luzern, Switzerland
      notes:
      url:  https://www.pilatus.ch/fileadmin/files/entdecken/aktivitaeten/wandern-am-pilatus/1.1.1.3_Wandern_am_Pilatus_5.pdf

    - name: Santis
      location:
      notes: 1700m ascent/descent
      url: http://www.hikr.org/tour/post67759.html

    - name: Alpstein 3 lakes
      location:
      notes:
      url: http://www.appenzell.ch/en/alpstein/hiking/hiking-tour-suggestions/the-mountain-lakes-of-the-alpstein.html

    - name: Santis-Altmann ridge
      location:
      notes:
      url: https://www.myswitzerland.com/en-us/summer-weather-nodes/good_weather_summer/adventure-weather-summer/adventure-sports-summer/hiking-outdoor/panorama-trails/hiking-the-ridge-between-mts-saentis-and-altmann.html

    - name: Lauterbrunnen
      location: Lauterbrunnen, Switzerland
      notes:
      url:

---

{% for r in page.completed %}
{% if r.date %}{{ r.date | date: "%-d %B %Y"  }}: {% endif %}[{{r.name}}]({{r.url}}){% if r.location %}, *{{r.location}}* {% endif %}{% if r.notes %} ({{r.notes}}){% endif %}{% if r.track %}{% for t in r.track %} [[GPS]({{t}})]{% endfor %}{% endif %}{% if r.photos %}, [photo]({{r.photos}}){% endif %}{% if r.private_photos %}, [private]({{r.private_photos}})]{% endif %}<br />{% endfor %}

### Wishlist
{% for r in page.wishlist %}
[{{r.name}}]({{r.url}}){% if r.location %}, *{{r.location}}* {% endif %}{% if r.notes %} ({{r.notes}}) {% endif %}<br />{% endfor %}
