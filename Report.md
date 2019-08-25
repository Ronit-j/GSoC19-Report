

<img src="https://camo.githubusercontent.com/ed508e9c66d718f76333215a139af24f8bb8fa8d/68747470733a2f2f6d75736573636f72652e6f72672f73697465732f6d75736573636f72652e6f72672f66696c65732f4361707475726525323064253237652543432538316372616e253230323031362d30332d303125323030392e34382e31315f302e706e67" align="center"/>

## Google Summer of Code 2019 Final Work Product - 

| **Student** | Ronit Jorvekar |
| --- | --- |
| **Github** | [@Ronit-j](http://github.com/Ronit-j)  |
| **Organisation**  | [Robocomp](https://robocomp.github.io/web/)  |
| **Project** | [Learning acceptable social behaviour using basic machine learning techniques on graph data](https://summerofcode.withgoogle.com/projects/#6234257968594944) |   

## **Aim**
This project aims at applying recent machine learning techniques to create a graph neural network model which predicts the social acceptability score of the robot given a scenario represented in graph.

## **Work Done**

My main task in the first coding period was to develop a REST service for distributed hyperparameter-tuning and design machine learning models using two frameworks [dgl](https://www.dgl.ai/) and [pytorch geometric](https://pytorch-geometric.readthedocs.io/en/latest/#). The models can be found [here](https://github.com/robocomp/sngnn/tree/master/models). In the second coding period, I integrated the work done in the first period and the work done by my mentor previously with Robocomp. I created 5 agents which help to create a Simulation of the Scenario which is then evaluated using the Graph neural network models developed previously. I also wrote documentation explaining the work done and how anyone interested in graph neural networks can develop them. This is the simple overview of the work done for more details you can check the blogs linked below and the repository.

## **SNGNN: [Github Repository](https://github.com/robocomp/sngnn)**

  * Pull Request : [Link](https://github.com/robocomp/sngnn/pull/1)
  

### **Graph Neural Network Models: [Github Repository Link](https://github.com/robocomp/sngnn/tree/master/models)**


### **Robocomp Agents: [Github Repository Link](https://github.com/robocomp/sngnn/tree/master/robocomp_agm)**


### **Social Navigation Scoring API: [Github Repository Link](https://github.com/robocomp/sngnn/tree/master/sndgAPI.py)**



## Screenshots
| Scenario 1 | Scenario 2 | Scenario 3|
|--- | --- | --- |
| <img src="https://raw.githubusercontent.com/Ronit-j/GSoC19-Report/master/sn1.png"/> |<img src="https://raw.githubusercontent.com/Ronit-j/GSoC19-Report/master/sn2.png" /> | <img src="https://raw.githubusercontent.com/Ronit-j/GSoC19-Report/master/sn3.png" />|


## Future Scope 
1. Develop manual editor for the social scenario
2. Add more functionality to the Social Navigation API

## Learnings
This experience has given me immense learnings:
1. Write clean code and develop solutions which are complete without using any work-arounds
2. Using git effectively
3. Writing documentation
4. Designing good structured code which is extensible
5. Work in a collaborative environment which required soft skills
6. Develop machine learning models in pytorch 


## Blog Posts

All of my blog posts related to my work can be found in the [Robocomp Blog](https://robocomp.github.io/web/gsoc/2019/index)


## Social

* Youtube Video showcasing the simulation :

[![Social Navigation](http://img.youtube.com/vi/QVvuywgomTE/0.jpg)](https://youtu.be/QVvuywgomTE "Social Navigation")


