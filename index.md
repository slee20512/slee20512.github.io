---
layout: about
permalink: /
profile:
  align: right
  image: profile_photo.jpg
published: true
---

{% capture md %}
Hi, I’m **Seojin Lee**, a Ph.D. student in the **Department of Psychology at Stanford University**, jointly advised by [Dr. Dan Yamins](https://stanford.edu/~yamins/) and [Dr. Kalanit Grill-Spector](https://psychology.stanford.edu/people/kalanit-grill-spector).

I’m broadly interested in uncovering the **computational principles of the visual cortex** that enables efficient and flexible visual perception. My research takes a two-way approach:
1. Building biologically-plausible deep neural networks inspired by the brain.
2. Using gaps between model and biological vision to gain insight into what makes the brain's computations unique – an iterative process towards better models of the visual brain. 

Currently, I study the organizing principles of the developing visual system, focusing on how the brain begins to structure itself even before visual experience. I model retinal waves as a potential driving force for optimizing neural wiring and feature learning. To do this, I use [topographic deep artificial neural networks (TDANNs)](https://github.com/neuroailab/TDANN) that simulate cortical organization across layers, aiming to understand how early retinal activity may support both efficient wiring and useful visual representations. 

Before Stanford, I earned my B.S. in Computer Science and B.A. in Cognitive Science from Johns Hopkins University, and worked as a research assistant in [Dr. Elias Issa](https://zuckermaninstitute.columbia.edu/elias-b-issa-phd)’s lab at Columbia University’s Zuckerman Institute. There, I investigated how geometry-based processing emerges in human vision. We showed that standard face recognition models exhibit strong texture bias and limited sensitivity to facial geometry, reducing their ability to generalize to new faces. We found that training with emotion-driven, within-identity variation can improve generalization. 

I’ve also had the privilege of working with [Dr. Solange Brown](https://neuroscience.jhu.edu/research/faculty/11) (Johns Hopkins School of Medicine) and [Dr. Taylor T. Johnson](https://www.taylortjohnson.com/) (Vanderbilt University, EECS), whose mentorship deeply shaped my interdisciplinary approach to studying vision and computation.

[**→ Learn more about my research**](/research)  
[**→ Why vision? Why research?**](/curiosity)  
[**→ View my CV**](/cv)
{% endcapture %}
{{ md | markdownify }}