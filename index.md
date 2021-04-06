## Introduction

This page is a minimal portfolio showcasing a selected number projects carried out by the author in his free-time. 
Following projects were selected to illustrate the author's capabilities in the use of the respective programming 
languages and problem-solving techniques.

This page is a work in progress and will be continuously updated to reflect authors activities. 

### Project 1: Track-Sys (Java/Kotlin/Typescript)  
#### _Overview_
Track-Sys is a complete system for tracking events. These can be anything where human activity is involve and 
some traceability is required for management purposes. 
The project consists of the following components: 
 - [a microservice for managing the associate data streams in the activity](https://github.com/Pendo720/TrackerMS)
 - [a web portal showing registered events in real-time](https://github.com/Pendo720/Track-Sys-Dashboard) 
 - [a mobile app for capturing event data](https://github.com/Pendo720/M-Front)
  
The following screenshots show the front-ends during possible operational scenarios.

**Web portal screenshot**

![](/gh-images/wfront.png)

**Mobile App screenshot**

![](/gh-images/mfront.png)

**Description**
>   The event of interest is generated using the proximity sensor of the mobile app. On submission - which happens when the button labelled 'POST' 
>   is clicked; the event data is posted to the backend. The backend registers the event and notifies any subscribed clients of the new event. 
>   The notifications from the backend is processed and the dashboard is updated to reflect the system changes.
 
 
### [Project 2: N2-Classifier (Java)](https://github.com/Pendo720/nn-fp)  
#### _Overview_
This is a customisable neural network created to consolidate understanding and applications of neural networks as problem solving technique. The code implements
an easily customisable model. 
The N2-Classifier is a minimalist application of Neural Network to classify a range of numbers based on their bit representation. It uses backpropagation to 
determine the optimal weight-set for the model. The implementation splits the input data range into three: training, cross-validation and testing datasets.
The model training and cross-validation dataset is use for determining the optimal number of necessary iterations during training. Thus, the model training terminates 
as soon as all cross-validation and tests have passed.

Using the trained model, a virtual robot arm is deployed to illustrate how such a model can be use to provide a solution to a given problem. By picking a number of 
network inputs which match to specific arm configurations; the network can be use to drive a real robot to perform some useful task.

This flexibility of the N2-Classifier and neural network demostrates the versatility of using such a technique in problem solving. The following screenshots show the 
N2-Classifier in operation.

|      |      |
|:----:|:----:|
| ![](/gh-images/Screenshot_0.png) | ![](/gh-images/Screenshot_01.png) |

|      |      |
|:----:|:----:|
| ![](/gh-images/Screenshot_16.png) | ![](/gh-images/Screenshot_05.png) |

**Description**
>
>

### [Project 3: Single-Value-SQM (Python)](https://github.com/Pendo720/svsqm)  
#### _Overview_
A common problem encountered when assessing the quality of software artifact is the absence of a standard
upon which comparisions of a given artifact can be assessed. The Single-value software quality metric is
practical framework for facilitating such comparisions. This project is an extension of my master's 
programme: software quality module. 

![](/gh-images/svsqm_graph.png)

In addition to providing a single-value metric for software quality, the visual above can help identify 
the aspect of the artifact qualities which need addressing to better its quality. The artifact quality 
measure is the average of the individual values on the four dimensions: Specification, Documentation, Implementation and Testing

Note: the quantities on both the Testing and Documentation dimensions are negated for visualisation purposes.

**Description**
> explain the benefit and possible application of such framework 


### [Project 4: k-Means Clustering (C++)](https://github.com/Pendo720/kmeans-fp)  
#### _Overview_
AI and ML in particular is finding use in different aspect of our daily life. As one of the pivotal 
components of AI, the ability to aggregate data on the basis of a given trait of the data(feature) has 
proven to be an effective means for acquiring insights into the data. k-Means algorithm is one of the 
unsupervised ML algorithms for grouping(clustering) data by means of some intrinsic traits in the data. 

**Description**
> - describe application(line-based robot) automation
> - implement it
> - document it all 
