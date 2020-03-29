---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


The central topic of my research is the development of adaptive software systems. Within the FESAS project I focused my dissertation on the aspect of reusability of software modules in adaptive systems, especially in distributed systems. 

From the beginning I tried not to limit the applicability of my approaches to certain system domains. Accordingly, I have applied the methods in several system domains related to Internet of Things (IoT) and Cyber-physical Systems (CPS) in recent years. 
To maximize the potential of adaptivity, I have cooperated with experts in the respective domains.

Another relevant topic besides software engineering and a broad diversity of domains is artificial intelligence.
Adaptive systems often operate in unknown or changing environments and are also characterized by changes in the system itself.
In order to be able to react adequately to such changes, the integration of machine learning and data mining methods is essential.
In the following, these three strands of my research are presented.


## Software Engineering for Adaptive Systems

The increasing complexity and size of information systems results in increased expenditure for their maintenance.
Additional complexity results from current trends in the areas of IoT and CPS, such as the miniaturization of computer devices, which leads to increased mobility of the systems and requires context-based adaptations.
Self-adaptive software systems have the ability to react to changes in their environment or in the system itself through adaptation.
This can be a solution to the challenges mentioned above.
However, the development of self-adaptive software systems is complex and tools are usually limited to certain application domains.
In particular, current approaches lack the extraction and reuse of generic building blocks for self-adaptive software systems.

In my doctoral thesis, I focused on reusability in the development of self-adaptive software systems in the FESAS project. 
The resulting FESAS framework supports developers of self-adaptive software systems through a clearly defined development process, which is mapped in development tools (based on the Eclipse IDE for software development) and test modules.
This development process is complemented by software modules that support communication, deployment of system components and definition of decision logic for adaptations.
Thus, the FESAS framework provides a construction kit for the simplified creation of self-adaptive software systems, which relieves developers of general tasks and supports them in the complex integration of adaptive capabilities.

Since systems of the categories IoT and CPS often consist of many distributed system units and the amount of information available through sensor technology has increased exponentially in recent years, the process of adaptation decisions is characterized by uncertainty.
This is aggravated by a gap between knowledge at development time and the conditions at runtime (e.g. also the actual characteristics of the system environment, which can diverge due to system mobility).
On the one hand, this can lead to resource conflicts between autonomous units of the system;
on the other hand, this results in inaccuracies in the rules, models or target definitions used to make adaptation decisions.
For this purpose, the FESAS framework integrates a module for self-optimization of the system through machine learning and meta-adaptation, i.e. adjustments of the decision logic for adaptations.
Although this module is optimized for use with the FESAS Framework, it is self-contained by encapsulation and can be used with other development tools.


## Internet of Things (IoT) and Cyber-physical Systems (CPS)

From the very beginning, the main goal of my PhD in the FESAS project was the broadest possible use of the findings in various system domains in the field of IoT and CPS.
In the context of my dissertation, I used the FESAS framework for the implementation of self-adaptive software systems in nine different system domains.
In many cases I cooperated with partners from practice and researchers from these domains.
The main task for me as a post-doc at the University of Würzburg is to establish a research group in the field of IoT and CPS.
Here we concentrate on the following domains: (1) Industry 4.0, (2) Intelligent Transport Systems, (3) Communication for IoT systems and (4) Learning / Training using virtual reality (especially in sports). 
Furthermore, we are researching in the areas of machine learning, wearables, and robotics as cross-cutting issues for the four topics.

In the area of Industry 4.0, we address the topics of predictive maintenance, optimization of warehousing and manufacturing processes as well as coordination of production robots and (autonomous) transport units. 
This is being done in new cooperations with industry partners such as io-consultants, Heidelberger Druckmaschinen, Bosch Rexroth, and Syntax (formerly Freudenberg IT).
In the field of intelligent transport systems (ITS), we focus on the coordination of semi-autonomous vehicles in convoys (so-called platooning).
In cooperation with PASS Consulting, we consider the topics of intelligent logistics and route planning with nature-inspired optimization methods as an intersection between ITS and Industry 4.0.
The mentioned mobility of IoT devices may require adjustments to the communication of the devices.
Therefore, communication in the field of IoT is another pillar of our research.
The focus is on the comparability of IoT protocols, especially in the area of vehicle-to-cloud communication, as well as adaptive adaptation of communication to current requirements and availability of communication channels.
In cooperation with TSG Hoffenheim, TSG ResearchLab, and Prof. Billy Sperlich, we conduct research in the field of data analytics and the use of virtual reality technologies for training of neuronal functions, performance analysis and prediction as well as optimization of training plans for professional and amateur athletes.
Furthermore, in the area of IoT and CPS I have active cooperations with researchers at the University of Mannheim in the areas of computational outsourcing with Cloud Computing, Edge Computing, Fog Computing, and IoT devices (cooperation with Dr. Janick Edinger and Prof. Christian Becker) as well as with Dr. Patricia Arias-Cabarcos from the Karlsruhe Insitut of Tehcnology in adaptive authentication using wearables and sensors.
Common cross-sectional topics for all areas are evaluation with (1) simulations or hardware testbeds, (2) by integrating data from real production systems or (3) by applying the methodologies/prototypes in real (test) systems.


## Application of machine learning in adaptive systems

The third thread of my research deals with data mining and machine learning. 
Basic for adaptive functionality of software is the analysis of the current state of the system and system environment or the prediction of future system and environment states as well as the planning of new system configurations to adapt to changes in the system or its environment.
Data mining methods and time series analyses are suitable for analysis.
One difficulty in the field of planning is that the possible combinations of system configurations represent extremely large search spaces.
To master these search spaces, stochastic or nature-inspired optimization approaches are often integrated.
Furthermore, techniques from the field of machine learning (e.g. reinforcement learning) are suitable for independently identifying desired system configurations at runtime.
The topics of machine learning are orthogonal to the other two topic blocks and are taken up in these.

My research contributions in this subject area are divided into three parts.
First, I have contributions that are related to software engineering.
These contributions support developers in the application of optimization methods for planning adaptation, the selection of machine learning algorithms for analyzing data, or simulation-based methods for learning adaptation decisions.
Furthermore, applied methods of machine learning in adaptive assistance systems, e.g. self-adaptive fall recognition systems and a crowdsourced barrier-free road map for the navigation of wheelchair users, are presented. 
Finally, I have contributions in the area of applied machine learning methods in cloud computing.
