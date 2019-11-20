---
layout: default
---

## Measuring Physical Profile and Use of Park Connector Network with Deep Learning and Multi-Source Multi-Modal Data Analytics

*Note! This is an ongoing research. 

The Park Connector Network is a series of publicly maintained greenways that links parks and opens spaces across Singapore. The project attempts to understand how people utilize these greenways in relation to its physical profile. The physical profile is captured and processed using a semantic segmentation models. The user activities are surveyed using a GoPro camera and the resulting videos are processed using action recognition models. Multiple regression analysis will then be performed on the resulting dataset. 

**Action Detection**

The survey of user activities is accomplished by processing the GoPro video through pre-trained object and action detection models. The demo below shows a visualization of the detections. Footage is blurred for privacy.

<video width="500" height="300" controls="controls">
  <source src="https://gxite.github.io/portfolio/video/crowd_action_demo.mp4" type="video/mp4" >
</video>

The code repository cade be found [here](https://github.com/gxite/pcn-acam) for reference. 


