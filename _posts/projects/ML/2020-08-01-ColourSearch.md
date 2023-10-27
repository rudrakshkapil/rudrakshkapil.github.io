---
title:  "Colour Density Estimation and Search"
layout: post
categories: project-ML
img: coloursearch.png
alt: "Example results"
---

**Skills**: Python, Jupyter, Computer Vision, Scikit-Image, OpenCV, Pytorch, CNNs, Oracle Database, Visual Search.


**Description**: In this project, I developed a model that could extract the colour distribution present in an image in order to identify the most common colours present. Various levels of granularity are possible, as shown on the left. This decomposition allows a simple searching method to be implemented, where the colours are transformed to CIELAB space, and the euclidian distance between the representations in this colour space are used as a measure of similarity between images.
 
This project was completed during my time as a Product Development intern at Oracle. I integrated this model into the Oracle meta-data search engine by adding colour tags for images of products in the database. 


<div style="display:flex;justify-content:center;align-items:center">
  <img src="{{ site.baseurl }}/resources/projects/{{ page.img }}" alt="{{ page.alt }}" style="width:500px;height:auto;justify-content:center">
</div>

