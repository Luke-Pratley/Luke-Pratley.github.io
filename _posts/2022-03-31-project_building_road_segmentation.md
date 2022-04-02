---
title: Extraction of buildings and road networks from Satellite Images
categories:
- Machine Learning
tags: 
- Python 
- Tensorflow 
- Keras 
- Pytest 
---
<!-- more -->

**Repository**: [Building and Road Segmentation](https://github.com/Luke-Pratley/building_road_segmentation) 
[![Python application](https://github.com/Luke-Pratley/building_road_segmentation/actions/workflows/building_road_segmentation_tests.yml/badge.svg)](https://github.com/Luke-Pratley/building_road_segmentation/actions/workflows/building_road_segmentation_tests.yml)



Below we display an example of an input image and the corresponding ground truth and predicted road network and building footprints.

### Input Image
<div style="text-align:center">
 
 <img src="https://raw.githubusercontent.com/Luke-Pratley/building_road_segmentation/getting_ready_for_submission/Vegas_input.png" /></div>

### Predicted Labels
<div style="text-align:center">
<img src="https://raw.githubusercontent.com/Luke-Pratley/building_road_segmentation/getting_ready_for_submission/Vegas_output.png" />
</div>

Humanitarian and natural disasters can impact roads and buildings, and having a tool that can quickly survey them is useful.
For this reason, I extract buildings and road networks from satellite images using Tensorflow and UNet archtectures.


