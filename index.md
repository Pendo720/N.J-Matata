## Introduction

This page is a minimal portfolio showcasing a selected number projects carried out during periods of my 
unemployed. The following projects were selected for their illustration of my capabilities in the
use of the respective programming languages and techniques.

### [Project 1: Single-value software quality metric - Python](https://github.com/Pendo720/svsqm)  
#### Overview
A common problem encountered when assessing the quality of software artifact is the absence of a standard
upon which comparisions of a given artifact can be assessed. The Single-value software quality metric is
practical framework for facilitating such comparisions. This project is an extension of my master's 
programme: software quality module. 

![](/gh-images/svsqm_graph.png)

In addition to providing a single-value metric for software quality, the visual above can help identify 
the aspect of the artifact qualities which need addressing to better its quality. The artifact quality 
measure is the average of the individual values on the four dimension.

Note: the quantities on both Test and Imp. are negated for visualisation purposes.

### [Project 2: k-Means Clustering - C++](https://github.com/Pendo720/kmeans-fp)  
#### Overview
AI and ML in particular is finding use in different aspect of our daily life. As one of the pivotal 
components of AI, the ability to aggregate data on the basis of a given trait of the data(feature) has 
proven to be an effective means for acquiring insights into the data. k-Means algorithm is one of the 
unsupervised ML algorithms for grouping(clustering) data by means of some intrinsic traits in the data. 

### [Project 3: Neural Network Classifier - Java](https://github.com/Pendo720/nn-fp)  
#### Overview
This is a customisable neural network created to consolidate understanding of neural networks. The code implements
an easily customisable network. The architectural customisation entails configuration of both layers and the neurons 
in each of the layer. This flexibility enables use of the network in diverse problem scenarios.

### [Project 5: Event Generator - Kotlin](https://github.com/Pendo720/nfc-eg)  
#### Overview
Using an Android device, created an event generator by exploiting one of the device intrisic sensors. The project is
part of [RT-Event Router - Java/Angular](https://github.com/Pendo720/Tri-Font). It provides a mechanism for verifying 
the RT-Event Router.

Created:
  - an event generator using Android device sensor
  - propagated generated event to a backend subsystem described in [Project 4](https://github.com/Pendo720/Tri-Font) - which routes received events to subscribers. 

### [Project 4: RT-Event Router - Java/Angular](https://github.com/Pendo720/Tri-Font)  
#### Overview

Created:
  - a microservice for processing events, broadcasting any received events to subscribers
  - created a front-end which subscribes to the microservice endpoint and updates in real-time  
