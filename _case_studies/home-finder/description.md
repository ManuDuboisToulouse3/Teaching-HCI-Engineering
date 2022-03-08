---
layout: case-study
permalink: /case_studies/home-finder/description.html
title: Home Finder
authors:
    - author: 
        name: Philippe
        surname: Palanque
        url: "https://www.irit.fr/recherches/ICS/people/palanque/"
    - author:
        name: Célia
        surname: Martinie
        url: "https://www.irit.fr/recherches/ICS/people/martinie/index.html"
type: Exercise
application-domains: 
  - Databases
interaction-techniques:
    - WIMP
current-students: "Computer Science"
student-level: M1
HCI-theme: "Engineering interactive applications"
tools: 
     - "Java Swing"
     - "Netbeans"    
brief-description: "The Home Finder is an interactive application allowing the editing and the visualisation of a real estate database. It is composed of two main windows. The first one enables the user to edit the database. The second one enables the user to filter real estate according to different criteria (surface area, distance from the workplace, etc.) and to view the details of a selected real estate."
---

## Targeted students and prerequisites
The main target type of student is a person enrolled in a Master in Computer Science which has been tuned to address interactive critical system aspects~\cite{ref9}, and following the learning unit named \enquote{Interactive Systems Software Engineering}. The main prerequisite is to have basic knowledge about databases, as well as about the Java Swing graphical toolkit for the programming of user interfaces.

## Objectives
The main objective is to make the students understand that most of the code is dedicated to UI and that to program functions for users to add/modify/remove data is complicated. In addition, this exercise also aims to highlight that:

* the design of the UI can be relatively independent from the functional core users' tasks have to be identified,
* multiple interfaces are possible for a given task,
* some design solutions are more usable than others.

## Pedagogical steps/monitoring, initial materials and tools
This exercise is the last exercise in the pedagogical progression of the learning unit "Interactive Systems Software Engineering" and tackles the programming of a user interface from a behavioral specification of a UI. The students have previously learned to read and to build a behavioral specification of interactive systems behavior. They also have previously learned a method to program a user interface from a specification composed of a layout picture for the presentation part of the user interface and of a textual description for the behavioral part of the user interface. 

This method is composed of 5 steps:

    1. Identify all possible events
    
    2. Identify all possible actions
    
    3. Build the automaton to describe the behavior of the UI
    
    4. From the automaton, produce the state/event matrix
    
    5. Program source code for event handlers

The students have already applied this method on very simple exercises and then on exercises with an increasing level of difficulty (increasing number of states and of events to be managed). For this exercise, the students have already produced the automaton and state/event matrix.
We provide the students with the following statement:

> You will conceive an interactive application allowing the editing and the visualization of the real estate database. The entries from the database can be manipulated via the editing interface of Figure 1 which behaves as specified in the automaton produced and validated during supervised work session 3 (at a previous stage of the learning unit). This interface allows adding, modifying or deleting entries in the database. This information can be visualized via the visualization interface in Figure 2 which behaves as specified in the automaton produced and validated during supervised work session 3 (at a previous stage of the learning unit). This interface allows you to filter real estate according to different criteria (surface area, distance from the workplace, etc.) and to view the details of a selected real estate (Visual Information Seeking Mantra by Shneiderman: Overview first, zoom and filter, then details-on-demand).

The students have to focus on implementing the user interfaces to be compliant with the specifications and on organizing the software using the Seeheim software architecture.

They have to use the Java Swing graphical toolkit and the NetBeans Integrated Development Environment.

<img src="assets/fig5.png" width=400 style="max-width: 400px" alt="Database editing user interface of the Home Finder">

_Figure 1: Database editing user interface of the Home Finder_

![Figure 2](assets/fig6.png)
_Figure 2: Visualisation user interface of the Home Finder_


## Expected output and evaluation
The expected output is a software archive containing the code source of the program of the Home Finder user interface, as well as an executable version of the Home Finder. The evaluation focuses on the consistency between the specification automaton and the program, as well as on the consistency between the software architecture and the Seeheim architecture.
The evaluation grid for the exercise is as follows:

* Programming method
  * Compliance with the automaton and state/event matrix: 5 points
  * Software project preparation in the NetBeans IDE: 1 point
  * Compliance of the UI layout with the specification: 1 point
  *  One to one mapping between a UI component and an event handler: 1 point
  *  One to one mapping between a column of the state/event matrix and the event handlers in the code: 1 point
* Coding rules
   * Java coding rules followed: 2 points
   * Legibility (explicit naming of variables, methods and functions…) and correct usage of the IDE refactoring commands: 2 points
   * Software architecture compliant with the Seeheim architecture: 2 points
* Functioning
   * The UI runs as specified: 5 points
