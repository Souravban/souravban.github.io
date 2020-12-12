---
layout: project
type: project
image: images/TGS_Salt_Identification_Challenge_icon_gif.gif
title: <center>TGS Salt Identification</center>
permalink: projects/Salt
# All dates must be YYYY-MM-DD format!
date: <center>2020-02-16</center>
labels:<center>
  - Machine Learning
  - Deep Learning
summary: <b><center>Trying to gain insights on how to find Salt Deposits below the Earth's surface efficiently.</center></b>
---

<img class="ui image" src="../images/TGS_Salt_Identification_Challenge_Banner.png">

Several areas of Earth with large accumulations of oil and gas also have huge deposits of salt below the surface. But unfortunately, knowing where large salt deposits are precisely is very difficult. Professional seismic imaging still requires expert human interpretation of salt bodies. This leads to very subjective, highly variable renderings. More alarmingly, it leads to potentially dangerous situations for oil and gas company drillers.

To create the most accurate seismic images and 3D renderings, TGS (the world’s leading geoscience data company) is hoping Kaggle’s machine learning community will be able to build an algorithm that automatically and accurately identifies if a subsurface target is salt or not.

Seismic data is collected using reflection seismology, or seismic reflection. The method requires a controlled seismic source of energy, such as compressed air or a seismic vibrator, and sensors record the reflection from rock interfaces within the subsurface. The recorded data is then processed to create a 3D view of earth’s interior. Reflection seismology is similar to X-ray, sonar and echolocation.

A seismic image is produced from imaging the reflection coming from rock boundaries. The seismic image shows the boundaries between different rock types. In theory, the strength of reflection is directly proportional to the difference in the physical properties on either sides of the interface. While seismic images show rock boundaries, they don't say much about the rock themselves; some rocks are easy to identify while some are difficult.

There are several areas of the world where there are vast quantities of salt in the subsurface. One of the challenges of seismic imaging is to identify the part of subsurface which is salt. Salt has characteristics that makes it both simple and hard to identify. Salt density is usually 2.14 g/cc which is lower than most surrounding rocks. The seismic velocity of salt is 4.5 km/sec, which is usually faster than its surrounding rocks. This difference creates a sharp reflection at the salt-sediment interface. Usually salt is an amorphous rock without much internal structure. This means that there is typically not much reflectivity inside the salt, unless there are sediments trapped inside it. The unusually high seismic velocity of salt can create problems with seismic imaging.

<b>Problem Statement</b> : In TGS Salt Identification Challenge, we are trying to find the more insights on how to find deposits of salt below the surface correctly.

<b>Source</b> : [https://www.kaggle.com/c/tgs-salt-identification-challenge/data](https://www.kaggle.com/c/tgs-salt-identification-challenge/data)

<b>Data Description</b> : The data is a set of images chosen at various locations chosen at random in the subsurface. The images are 101 x 101 pixels and each pixel is classified as either salt or sediment. In addition to the seismic images, the depth of the imaged location is provided for each image. The goal of the competition is to segment regions that contain salt.

<b>Real-world/Business Objectives and Constraints</b> : 
1. The cost of a mis-classification very high.
2. No strict latency concerns.
3. It will help us to find deposits of salt below the surface correctly.

<h1><b>Ongoing Work</b></h1>

To learn more please visit : [Here](https://github.com/Souravban/)
