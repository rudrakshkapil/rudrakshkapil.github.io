---
title:  "Deep Learning Framework to Detect Face Masks from Video Footage"
layout: post
categories: publication
img: cicn_face_masks.jpg
---
<!-- Aniruddha S. Joshi, Shreyas S. Joshi, Goutham Kanahasabi, **Rudraksh Kapil**, and Savyasachi Gupta -->
A. S. Joshi, S. S. Joshi, G. Kanahasabi, **R. Kapil**, and S. Gupta

#### *in IEEE 12th International Conference on Computational Intelligence and Communication Networks (CICN 2020), Nainital, India*


**Abstract**: The use of facial masks in public spaces has become a social obligation since the wake of the COVID-19 global pandemic and the identification of facial masks can be imperative to ensure public safety. Detection of facial masks in video footages is a challenging task primarily due to the fact that the masks themselves behave as occlusions to face detection algorithms due to the absence of facial landmarks in the masked regions. In this work, we propose an approach for detecting facial masks in videos using deep learning. The proposed framework capitalizes on the MTCNN face detection model to identify the faces and their corresponding facial landmarks present in the video frame. These facial images and cues are then processed by a neoteric classifier that utilises the MobileNetV2 architecture as an object detector for identifying masked regions. The proposed framework was tested on a dataset which is a collection of videos capturing the movement of people in public spaces while complying with COVID-19 safety protocols. The proposed methodology demon- strated its effectiveness in detecting facial masks by achieving high precision, recall, and accuracy.

<div class="button-container">
  <div class="more"><a href="https://ieeexplore.ieee.org/document/9242625">View on IEEE Xplore</a></div>
  <div class="more"><a href="https://arxiv.org/abs/2011.02371">View on arXiv</a></div>
</div>

<!-- ![Image alt]({{ site.baseurl }}/resources/publications/cicn_face_masks.jpg "Face Mask Detection Results") -->
<div style="border-radius: 60px; border-color:rgb(1,160,73);width:99%;margin-top:10px">
  <img src="{{ site.baseurl }}/resources/publications/{{ page.img }}"/>
</div>