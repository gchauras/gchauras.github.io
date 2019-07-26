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

    - title:   "Table Information Extraction Based on PDFMiner "
      author:  "H. Liu, M. Ge, etc."
      journal: "Manuscript"




---

Includes: [Publications](#Publications), [Patent](#Patent), [Major Projects](#Major Projects)

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
	- The goal is to extract the tabular data from the PDF file based on PDFminer in the field of Biochar. The reason for doing this is that there are often a lot of papers in this field that contain tabular data and therefore it is often time consuming to extract data manually. Besides, unlike the field in some medical field, most forms in the bioenergy field are presented as a three-line table so we could consider a general approach to parsing and extracting these tables. <br />
	- Project homepage: [[Website](https://github.com/text-mining-project/Table-information-extraction)]

<br />
	
- **Intelligent Mobile Rover Design**<br />
	- The goal is to design and assemble a automatic mobile rover to accomplish prescribed tasks including line tracing, color matching, ultrasonic rangingradar navigation, manipulator design, wireless communication etc. The major hardwares we use include Raspberry Pi, mbed, FGPA, camera, DC motor; and the software is mainly implemented in python and C++. <br />
	- Project homepage: [[Website](https://github.com/MasterEndless/Mobile-Rover-Design)]

<br />
	
- **Design of a Vision Protector Based on Binocular Ranging Algorithm**<br />
	- The goal is to design a vision protector which can relieve visual fatigue and protect eye health. The innovation of this design lies in relieving visual fatigue by using intelligent algorithm in computer vision instead of traditional ultrasonic ranging to measure the distance between users and books.Also, it solves all problems of existing vision protectors perfectly (advantages include: non-contacting, accurate, high fault tolerance, convenient).   <br />
	- Project homepage: [[Website](https://github.com/MasterEndless/Mobile-Rover-Design)]

<br />
	
- **Design of a Crossbar Switch System by VHDL**<br />
	- This project aims at designing a data packet routing system by VHDL to tackle communication between different modules in a common bus.   <br />
	- Project homepage: [[Website](https://github.com/MasterEndless/Crossbar-Switch-System-Deisgn)]

<br />
	
- **Implementation of Three Different Coding Techniques**<br />
	- This project aims at implementing Shannon, Fano and Huffman coding on "A Game of Thrones".   <br />
	- Project homepage: [[Website](https://github.com/MasterEndless/Information-Theory-coding-research)]	
	
------

