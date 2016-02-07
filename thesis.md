---
layout: page
permalink: /research/thesis/
title: "Algorithms & Perceptual Analysis for Interactive Free Viewpoint Image-Based Navigation"
---

## Abstract

We present image-based rendering that allows free viewpoint walkthroughs of urban scenes
using just a few photographs as input. Commercial applications such as Google Streetview,
Bing Maps etc. use rudimentary forms of image-based rendering for urban visualization;
more sophisticated approaches use the full 3D model of the scene as input.
As the quality of 3D model degrades, rendering artifacts are observed which drastically reduce the
utility of such applications. In this thesis, we propose image-based approximations to compensate
for the lack of accurate 3D geometry. In the first approach, we use discontinuous
image warping guided by quasi-dense depth maps which improves visual quality compared to
previous methods that rely on texturing 3D models. This approach involves a small degree
of manual intervention to mark occlusion boundaries in the input
images. We build upon this in the second approach by developing a completely automatic solution
that is capable of handling more complex scenes. We oversegment input images into superpixels
and warp them independently using sparse depth. We introduce depth synthesis to create approximate
depth in poorly reconstructed regions of the image and use this with our
image warps for generating high quality results. We compare our results to many
recent algorithms and show that our approach extends very well to free viewpoint navigation.

We also perform perceptual analysis of different image-based rendering
artifacts in separate user studies under controlled conditions. We use
vision science to investigate perspective distortions produced when a single image is projected
on a planar geometry and viewed from novel viewpoints. We use the experimental data to
develop a quantitative framework for predicting the level of perspective distortions as a
function of capture and viewing parameters. In another study, we compare artifacts caused by
smooth transitions (blending images) with abrupt transitions (popping) and
develop guidelines for selecting the ideal tradeoff under different capture and
rendering scenarios. We use guidelines from these studies to motivate the design
of our image-based rendering systems described above.

We demonstrate an application of our approach for cognitive therapy. We create the first
virtual reality application that uses image-based rendering instead of traditional
computer graphics. This drastically reduces the cost of modeling 3D scenes for
virtual reality while producing highly realistic walkthroughs.

Overall, we believe our work is a significant step towards free viewpoint image-based rendering
designed on sound perceptually-based foundations.


----

  * [Low res version](http://tel.archives-ouvertes.fr/docs/00/97/99/13/PDF/thesis.pdf) (15 MB): hosted at [HAL-INRIA](http://hal.inria.fr/index.php?halsid=d2p3vgd7l7v5iv7dqapvo20204&view_this_doc=tel-00979913&version=1) and [tel-archives](http://tel.archives-ouvertes.fr/tel-00979913)
  * [High res version](http://www-sop.inria.fr/reves/Basilic/2014/Cha14/thesis.pdf) (177 MB): hosted at [INRIA](http://www-sop.inria.fr/reves/Basilic/2014/Cha14/)

_Results and comparison figures are best appreciated on a computer screen using the high res version._

----

## Supplementary videos
  * [Chapter 3: Silhouette-aware warp results and comparisons](http://vimeo.com/62038846)
  * [Chapter 3: Silhouette-aware warp extra results](http://www-sop.inria.fr/reves/Basilic/2011/CSD11/#warpibr_results)
  * [Chapter 4: Superpixel warp results and comparisons](http://vimeo.com/62038844)
  * [Chapter 4: Superpixel warp extra results](http://vimeo.com/62038845)
  * [Chapter 5: Perception of perspective distortions](http://vimeo.com/64144141)
  * [Chapter 5: Perception of rendering artifacts](http://www.youtube.com/watch?v=akaWUe0mum8) The experiment 2 in the Section 5.2.3 of the thesis corresponds to experiment 3 in the video. Experiment 2 of this video is not a part of the thesis.
  * [Chapter 6: Virtual reality using image-based rendering results](http://vimeo.com/86704077)
