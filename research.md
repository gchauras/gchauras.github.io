---
layout: page
permalink: /research/
title: Research
pubs:

    - title:   "A Novel Maze Representation Approach for Finding Filled Path of A Mobile Robot"
      author:  "C. Zheng, H. Liu, M. Ge, Y. Liu"
      journal: "2019 International Conference on Computer, Network, Communication and Information Systems"
      note:    "CNCI 2019"
      year:    "2019"
      url:     "https://download.atlantis-press.com/article/125906938.pdf"
      doi:     "https://www.atlantis-press.com/proceedings/cnci-19/125906938"


    - title:   "Deep joint demosaicking and denoising"
      author:  "M. Gharbi, G. Chaurasia, S. Paris, F. Durand"
      journal: "ACM Transactions on Graphics"
      note:    "SIGGRAPH Asia"
      year:    "2016"
      url:     "https://groups.csail.mit.edu/graphics/demosaicnet/"
      doi:     "http://dx.doi.org/10.1145/2980179.2982399"


    - title:   "Multi view intrinsic decomposition & relighting"
      author:  "S. Duchene, C. Riant, G. Chaurasia, J. Lopez-Moreno, PY Laffont, S. Popov, A. Bousseau, G. Drettakis"
      journal: "ACM Transactions on Graphics"
      note:    "presented at SIGGRAPH"
      year:    "2015"
      url:     "http://www-sop.inria.fr/reves/Basilic/2015/DRCLLPD15/"
      doi:     "http://dx.doi.org/10.1145/2790060.2790063"
      image:   "http://www-sop.inria.fr/reves/Basilic/2015/DRCLLPD15/ateaser.jpg"

talks:

    - venue:  "Microsoft Research Redmond"
      date:   "July 19, 2013"
      url:    "http://research.microsoft.com/apps/video/dl.aspx?id=198331"

    - venue:  "MIT CSAIL"
      date:   "Sept 11, 2013"
      url:    "/research/talks/csail_2013/"
      internal: "1"


grant_reviews:
    - title: "National Science Foundation (USA)"
      url: "https://www.nsf.gov"
      years:
        - year: 2017

    - title: "Agence Nationale de la Recherche (France)"
      url: "http://www.agence-nationale-recherche.fr"
      years:
        - year: 2018

journal_reviews:

    - title: "ACM Transactions on Graphics"
      url:   "http://tog.acm.org"
      years:
        - year: 2016
        - year: 2017
        - year: 2018


conference_reviews:

    - title: "SIGGRAPH"
      years:
        - year: 2012
          url:  "http://s2012.siggraph.org/"
        - year: 2016
          url:  "http://s2016.siggraph.org/"


---

Jump to [Publications](#peer-reviewed-publications), [Thesis](#doctoral-thesis), [Media](#media-coverage), [Reviewing](#professional-service)

---

## Peer reviewed publications

{% assign thumbnail="right" %}

{% for pub in page.pubs %}
<!-- {% if pub.image %}
{% include image.html url=pub.image caption="" height="80px" align=thumbnail %}
{% endif %} -->
{{pub.author}}<br />
**{{pub.title}}**<br />
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} *{{pub.year}}*  [[web]({% if pub.internal %}{{pub.url | prepend: site.baseurl}}{% else %}{{pub.url}}{% endif %})] {% if pub.doi %}[[doi]({{pub.doi}})]{% endif %}

{% endfor %}

-----

## Doctoral thesis

**Algorithms & perceptual analysis for interactive free viewpoint image-based navigation** [[web]({{ "/research/thesis/" | prepend: site.baseurl}})]<br />
*Adviser: [George Drettakis](http://www-sop.inria.fr/members/George.Drettakis)* <br />
[INRIA](http://www.inria.fr/sophia), 2014

------

## Media coverage

{% for pub in site.data.cv.publications %}
{% if pub.media %}
- {{pub.title}} ({{pub.note}}, {{pub.year}}){% for article in pub.media %}
    - [{{article.url}}]({{article.url}}){% endfor %}
{% endif %}

{% endfor %}

------

## Professional service

- Grant proposals{% for review in site.data.cv.reviews.grants %}
    - {{review.title}} {% for y in review.years %} [{% if review.url %}[{{y.year}}]({{review.url}}){% else %}{{y.year}}{% endif %}] {% endfor %}<br />{% endfor %}

- Conference reviews{% for review in site.data.cv.reviews.conference %}
    - {{review.title}} {% for y in review.years %} [{% if y.url %}[{{y.year}}]({{y.url}}){% else %}{{y.year}}{% endif %}] {% endfor %}<br />{% endfor %}

- Journal reviews{% for review in site.data.cv.reviews.journal %}
    - {{review.title}} {% for y in review.years %} [{% if review.url %}[{{y.year}}]({{review.url}}){% else %}{{y.year}}{% endif %}] {% endfor %}<br />{% endfor %}
