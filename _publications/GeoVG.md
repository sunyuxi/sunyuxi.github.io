---
title: "Visual Grounding in Remote Sensing Images"
permalink: /publication/GeoVG
---

![Two examples demonstrate the differences between visual grounding in natural images and visual grounding in remote sensing images](https://sunyuxi.github.io/images/cmpRSNatural.jpg)

<small>Ground object retrieval from a large-scale remote sensing image is very important for lots of applications. We present a novel problem of visual grounding in remote sensing images. Visual grounding aims to locate the particular objects (in the form of the bounding box or segmentation mask) in an image by a natural language expression. The task already exists in the computer vision community. However, existing benchmark datasets and methods mainly focus on natural images rather than remote sensing images. Compared with natural images, remote sensing images contain large-scale scenes and the geographical spatial information of ground objects (e.g., longitude, latitude). The existing method cannot deal with these challenges. In this paper, we collect a new visual grounding dataset, called RSVG, and design a new method, namely GeoVG. In particular, the proposed method consists of a language encoder, image encoder, and fusion module. The language encoder is used to learn numerical geospatial relations and represent a complex expression as a geospatial relation graph. The image encoder is applied to learn large-scale remote sensing scenes with adaptive region attention. The fusion module is used to fuse the text and image feature for visual grounding. We evaluate the proposed method by comparing it to the state-of-the-art methods on RSVG. Experiments show that our method outperforms the previous methods on the proposed datasets.

[Download dataset here](http://academicpages.github.io/files/paper1.pdf)
