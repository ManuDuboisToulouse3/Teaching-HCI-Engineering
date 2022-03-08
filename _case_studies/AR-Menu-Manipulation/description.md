---
layout: case-study
title: AR-menu manipulation for a graphical editor
authors:
    - author: 
        name: Emmanuel
        surname: Dubois
        url: "https://www.irit.fr/~Emmanuel.Dubois/"
    - author:
        name: Mathieu
        surname: Raynal
        url: "https://www.irit.fr/~Mathieu.Raynal/"
type: Exercise
application-domains: 
  - Graphical authoring tool
interaction-techniques:
    - Augmented Reality for input interaction
current-students: Computer Science, HCI
student-level: M2
HCI-theme: Augmented Reality development
tools: 
     - Marker-based API
     - Java
brief-description: "The AR-menu manipulation is an interaction technique based on the manipulation of physical object to trigger the execution of 
predefined commands of an existing graphical tool. 

The goal is twofold: 1) illustrate how easy it can be to implement a robust AR interactive system with on-the-shelf devices 
and common technologies; 2) provide a case study in which multimodalities are provided in a redundant way (AR vs WIMP)."
---
## Targeted students and prerequisites
Targeted students are Master students in their second year, and following the unit named “Interaction modalities and Application domain” (M2 – HCI, Toulouse). 
They need to have a solid background in Java programming and to know how to modify the default settings of a development environment. 

## Objectives
The main objective is to bring the students to the development of a robust Augmented Reality prototype. 
It is based on the use and identification of physical markers via an USB camera. 
Physical manipulation of the markers (attached to physical objects) activate and manipulate menus and pointers.

The menus and pointers are those of a graphical editor provided at the beginning of the project with a documented API.
Tag detection is based on an existing java library provided at the beginning of the project.


## Pedagogical steps/monitoring, initial materials and tools
The project is decomposed into three steps:

-	setting up the programming environment to enable the execution of a very basic example developed with the same library. Preparing a workspace based on external JAR and DLL? an appropriate JDK and existing source files is not easy but represent one of the current difficulties for developing AR applications.

-	simple exercises to discover the main features of the tab detection library: identification of a tag; triggering a simple event; detecting and reacting to an orientation and distance of a tag; displaying feedback in an appropriate manner around the tag.

-	development of interaction techniques that can be used to control the main features of a graphical editor (JAR provided). In fact, students have also developed their own JAR file of this editor in a previous teaching unit, but for simplicity reason, one common implementation is proposed to avoid any problem due to an issue in this part of the project (otherwise manged in the other teaching unit)


## Expected outputs and Evaluation
The expected outcome is to successfully articulate the AR interaction technique with the graphical editor for a maximum of the features offered by the editor: 
form creation, form selection, form modification, multi-selection, absolute control of the cursor and relative control of the cursor thus allowing clutching.

The evaluation therefore only considers their ability to implement a solution based on existing AR library and application kernel.
