## Introduction

This page is a minimal portfolio showcasing a selection of projects carried out by the author in his free-time. 
The following projects were selected to illustrate the author's capabilities in the use of the respective programming 
languages and problem-solving techniques.

This page is a work in progress and will be continuously updated to reflect understanding and other related activities. 

### Project 1: Track-Sys (Java/Kotlin/Typescript)  
#### _Overview_
Track-Sys is a complete system for tracking events. The types of events considered encompasses everything where traceabilty is mandated in the management and processing of human activity. The complete project implementation consists of the following components: 
 - [TrackerMS](https://github.com/Pendo720/TrackerMS)
 - [Track-Sys-Dashboard](https://github.com/Pendo720/Track-Sys-Dashboard) 
 - [M-Front](https://github.com/Pendo720/M-Front)
TrackerMS was initially developed in C# with an SQL Server database.  

#### TrackerMS ####
This is a microservice for managing the associate data streams in the activity; implemented in Java with a Postgres database for storing events data. The service provides a limited set of the CRUD functions as per the percieved user requirements.  

#### Track-Sys Dashboard ####
This is a web portal showing registered events in real-time, it serves as a client to the microservice providing a neat view of the events and a single means for updating each event. The modular implementation of the portal using Typescript components facilitates possible extension/enhancement of the application to provide some of the other CRUD functions.

**Web portal screenshot**

![](/gh-images/wfront.png)


#### M-Front ####

M-Front is the event generation subsyste implemented as an Android app.  This minimalist app enables generation of easily customisable events using its host proximity sensor. Using this sensor on the ensured fast event generation with ease; something which was necessary for validating the resilience of the system.

**M-Front App screenshot**

![](/gh-images/mfront.png)

**Description**
>   The event of interest is generated using the mobile app. On submission - which happens when the button labelled 'POST' 
>   is clicked; the app posts the generated event data to the backend. This is registered at the backend which notifies any subscribers to the backend. 
>   The notifications from the backend is processed and the dashboard updated to reflect the system state.
>   
The system is capable of capturing event data in real-time and relay it to any observers be it other backend systems or frontends. 
 
 
### [Project 2: N2-Classifier (Java)](https://github.com/Pendo720/nn-fp)  
#### _Overview_
This is a customisable neural network developed to consolidate my understanding of neural networks and their application as a problem solving technique. The code implements
an easily customisable model from first principles. N2-Classifier is an application of neural network to classify a range of numbers based on their bit representation. It uses backpropagation to determine the optimal weights-set for the model. The implementation splits the input data range into three: training, cross-validation and testing datasets.
The model training and cross-validation dataset is use for determining the optimal number of necessary iterations during training. Thus, the model training terminates 
as soon as all cross-validation and tests have passed.

Using the trained model, a virtual robot arm is deployed to illustrate how such a model can be use to provide a solution to a given problem. By picking a number of 
network inputs which match to specific arm configurations; the neural network is deployed to simulate the robot arm transitioning between the selected configurations.
The following screenshots show the N2-Classifier in operation.

|      |      |
|:----:|:----:|
| ![](/gh-images/Screenshot_0.png) | ![](/gh-images/Screenshot_01.png) |

|      |      |
|:----:|:----:|
| ![](/gh-images/screenshot_21.png) | ![](/gh-images/screenshot_20.png) |

**Description**
> The first two screenshots show the N2-Classifier being exercised when the app starts up. The app instantiates a neural network model with a given configuration and starts training it using sample data generated from the configuration input. The training is checked through the use of the cross-validation dataset after every fixed number of iterations and is terminated when the model has converged as determined by the success of all cross-validation tests. After successful excution of the cross-validation tests, the model is then subjected to the standard tests before its deployment.     
> The last screenshots show a possible application of the classifier to perform state transition between defined robot arm configurations.
> 

### [Project 3: Single-Value-SQM (Python)](https://github.com/Pendo720/svsqm)  
#### _Overview_
A common problem encountered when assessing the quality of software artifact is the absence of a standard
upon which comparisions of a given artifact quality can be assessed. The single-value software quality metric is a visually 
practical framework for facilitating such comparisions. This project is a byproduct of an exploration into software quality carried out during my master's 
programme: software quality module. 

 ![](/gh-images/svsqm_graph.png)

In addition to providing a single-value metric for software quality, the visual helps identify those aspects of the quality criteria which need to be improved to better the software artifact quality. The framework defines software measure as the average of the individual values on the four dimensions: Specification, Documentation, Implementation and Testing

Note: the quantities on both the Testing and Documentation dimensions are negated for visualisation purposes only.

**Description**
> SVQM framework is a useful QA tool as it provides a birds-eye view of software quality. It can be use to introduce and encourage engineers in adopting 
> an organisation's quality strategy. The specifics of how to interpret and determine the values for the four dimensions is dependent on 
> the overall organisation's quality criteria. With such a framework, the main challenge to ensure good software quality is reduced to determining the
> the main factors on each quality dimension and defining quantitative values for these factors.
> 
> By interfacing the the SVQM framework to a trained neural network such as the N2-Classifier described above; it is possible to create an automated quality assurance 
> system - something which can provides real-time feedback to software development teams.

   
### [Project 4: k-means Clustering (C++)](https://github.com/Pendo720/kmeans-fp)  
#### _Overview_
AI and ML in particular is finding use in different aspect of our daily life. As one of the pivotal 
components of AI, the ability to aggregate data on the basis of a given trait in the data(feature) has 
proven to be an effective means for acquiring insights. k-means algorithm is one of the unsupervised 
ML algorithms for grouping(clustering) data by means of some properties of the data.

**Description** 
> In this project an implementation of k-means algorith is presented in C++ on a linux environment for the sole purpose of understanding the algorithm as illustrated by the
> example. As an on-going tool for enhancing my knowledge in the field of AI/ML, this project will be updated as time goes by to reflect my learning.
> The screenshot shows a run of the algorithm using randomly generate sample data. It is supplied with four centroids and four respective labels for these centroids.
> 

![](/gh-images/kmeans_run.PNG)
 
The screenshot show the adjustments on the centroid as a result of the run and a correct classification of the validation sample data.
 

