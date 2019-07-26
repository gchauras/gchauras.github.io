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


prepared:

    - title:   "Automatic Image Quality Assessment of Fetal Sonographic Image by Convolutional Networks "
      author:  "H. Luo, H. Liu, B. Zhang, K. Li"
      journal: "Physics in Medicine & Biology"
      note:    "Under reviewing"


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

Jump to [Publications](#Publications), [Thesis](#Patent), [Media](#media-coverage), [Reviewing](#professional-service)

---

## Publications

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

{% for pub in page.prepared %}
<!-- {% if pub.image %}
{% include image.html url=pub.image caption="" height="80px" align=thumbnail %}
{% endif %} -->
{{pub.author}}<br />
**{{pub.title}}*<br />
*{{pub.journal}}*
{% if pub.note %} *({{pub.note}})*
{% endif %} 

{% endfor %}



-----

## Patent

**Anti-visual Fatigue Multifunctional Table Lamp** [[pdf](https://github.com/MasterEndless/Personal-Files/blob/master/Anti-visual%20fatigue%20multifunctional%20table%20lamp.pdf?raw=true)]<br />
*Patent Number: 2018112399222*<br />

------

## Major Projects
- **Table Information Extraction Based on PDFMiner**<br />
	- Introduction: The goal is to extract the tabular data from the PDF file based on PDFminer in the field of Biochar. The reason for doing this is that there are often a lot of papers in this field that contain tabular data and therefore it is often time consuming to extract data manually. Besides, unlike the field in some medical field, most forms in the bioenergy field are presented as a three-line table so we could consider a general approach to parsing and extracting these tables. <br />
	- Project homepage: [[Website](https://github.com/text-mining-project/Table-information-extraction)]
	
- **Intelligent Mobile Rover Design**<br />
	- Introduction: The goal is to design and assemble a automatic mobile rover to accomplish prescribed tasks including line tracing, color matching, ultrasonic rangingradar navigation, manipulator design, wireless communication etc. The major hardwares we use include Raspberry Pi, mbed, FGPA, camera, DC motor; and the software is mainly implemented in python and C. <br />
	- Project homepage: [[Website](https://github.com/text-mining-project/Table-information-extraction)]


------

## Professional service

- Grant proposals{% for review in site.data.cv.reviews.grants %}
    - {{review.title}} {% for y in review.years %} [{% if review.url %}[{{y.year}}]({{review.url}}){% else %}{{y.year}}{% endif %}] {% endfor %}<br />{% endfor %}

- Conference reviews{% for review in site.data.cv.reviews.conference %}
    - {{review.title}} {% for y in review.years %} [{% if y.url %}[{{y.year}}]({{y.url}}){% else %}{{y.year}}{% endif %}] {% endfor %}<br />{% endfor %}

- Journal reviews{% for review in site.data.cv.reviews.journal %}
    - {{review.title}} {% for y in review.years %} [{% if review.url %}[{{y.year}}]({{review.url}}){% else %}{{y.year}}{% endif %}] {% endfor %}<br />{% endfor %}
