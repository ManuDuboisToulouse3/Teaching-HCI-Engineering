---
layout: case-study
title: Electronic Prescription System
authors:
   - author:
        name: José
        surname: Campos
        url: "https://www.di.uminho.pt/~jfc/index.shtml"
type: Project
application-domains:
   - Information system
   - Health 
interaction-techniques:
    - WIMP 
brief-description: "The Project consists in developing a system to support doctors in prescribing medicines. The project might be seen as part of a larger medical information system but, for the purpose of the project, only the act of prescribing medication is considered. One interesting aspect of the project are the constraints that are imposed on prescriptions: each prescription can only have up to three different medical products, and psychotropic medicines cannot be mixed with other substances in the same prescription. This can potentially create a distance between the doctor's goal of prescribing a treatment, and how the medical products needed for that treatment must be organized into prescriptions."
---

## Targeted students and prerequisites
The electronic prescription system project was first used in a third-year course on object-oriented analysis and design (OOAD). The students attending the course have taken several programming courses (functional, imperative, object oriented), as well as courses on algorithms, program synthesis, among others, but no course on Human-Computer Interaction. During the course, students must design and implement a software system. Experience shows that a) most students reach the course with a self-centered view of software development, and b) lack of knowledge about user interface design and development creates barriers for the successful design of even the business logic layer (and it undermines the step from requirements to software architecture). The electronic prescription system project has shown to be useful in raising students' awareness of user-centered concerns in the engineering of interactive computing systems.

The pre-requisite for the project is proficiency in object-oriented programming (although the project can also be framed in the context of web programming). The project runs in parallel with the course, in which students learn OOAD (resorting to [UML](https://martinfowler.com/books/uml.html)). Basic notions of HCI and user interface prototyping (for example, the MVC pattern) are also introduced (4h).

## Objectives
As stated above, from an HCI Engineering perspective, one objective of the project is to raise students' awareness of user-centered concerns. From that perspective, the focus is on taking into consideration user requirements and designing a user interface that addresses those requirements. Students will capture functional requirements in a use case model and later prototype a user interface to answer those requirements.

Use cases are analyzed in terms of how well they support the users in achieving their goals. Ideally, students will realize that the burden of organizing a list of medical products into valid prescriptions can be moved from the doctor to the system. Whether doctors will feel comfortable with that loss of control, however, needs to be validated.

At a later stage in the project, the students must design and implement a system that answers the identified requirements. This is done by first defining the API needed at the business logic layer (starting from the use case descriptions and user interface prototype), and then designing an appropriate architecture and implementing it. One goal, here, is to realize the impact that different user interface designs will have on the architecture of the system. For example, depending on the strategy used to validate/generate prescriptions, different APIs and supporting architectures will make sense at the business logic layer.

## Pedagogical steps/monitoring, initial materials and tools
The students self-organize in groups of 3 to 5 to carry out the project. The project is executed during the semester as the topics are worked on in class. Given its length the project is divided into three main steps: requirements, design, and implementation. Each stage is awarded a weight in the final grade (typically 30/30/40).

At the start of the project, students are provided with a copy of the Portuguese electronic medical prescription decree law, access to a database containing [information about human medicines](http://extranet.infarmed.pt/INFOMED-fo/index.xhtml).
}, and a set of scenarios describing how doctors prescribe medicines. Working from those scenarios, functional requirements are captured in a use case model. A user interface prototype is then produced to address usability concerns. The [Pencil tool](https://pencil.evolus.vn/) is introduced, but students are free to choose the prototyping tool of their choice.

During the design phase, students define the control logic for the user interface, the architecture of the system and behavioral models for the business logic. Modelling is done using UML diagrams. Students are encouraged to start by using pen and paper and later, once stable models are reached, a modelling tool (currently Visual Paradigm). In the final phase the system is implemented.

Mentoring is provided throughout the semester on students' request. One aspect that requires attention is managing the complexity of the proposed solution. The goal is to present the project as something realistic, that they could be developing professionally. Typically, students will propose systems that they are not able to fully implement in the timespan of the project. Managing and prioritizing requirements is also a skill the project aims to promote. This is challenging for students and guidance must be provided. One approach that has been attempted is to reduce the set of requirements to consider from phase to phase. However, this creates problems when the proposed solutions diverge on how requirements are handled. Additionally, it can cause frustration as students feel that they are not being allowed to pursue their initial idea for the system. An alternative approach is to define a minimum set of scenarios that the system should support.

After each stage, students must hand in a report describing what they have achieved. General feedback on the first two reports is given in class, commenting on the main positives and negatives of the submitted materials, as a whole. The final delivery must be defended by each group at the last week of the semester, and individual feedback is then provided. The defense includes a discussion of the final report and a demonstration of the system.

## Expected outputs and Evaluation

The expected outputs are the models mentioned above and the corresponding system implementation. More specifically, students should hand in: a use case model and a user interface prototype, from the first phase of the project; UML architectural and behavioural models for the system to be implemented; and the actual implementation and related deployment models.
The project contributes 9 points out of 20 to the final grade of the course. The other 11 points are distributed by a final exam (9 points) and a continuous evaluation component (2 points). Projects are graded based on an evaluation of the quality of requirements analysis, system design and system implementation:

* 2.7 points for the requirements analysis
* 2.7 points for the system's design
* 2.6 points for the implementation
* 1.0 point for report

Final project marks, however, are attributed on a per student basis. Each student's contribution to the project is evaluated using a peer assessment approach. Three times during the length of the project, students distribute a fixed number of points between the members of their group (themselves included) in a number of criteria that are discussed and agreed upon at the start of the project. For each criteria, the points to be distributed are a multiple of the group size so, in an ideal situation, all members of the group receive the same number of points. Each student's final mark in the project is the result of combining the project and peer assessment marks. Peer assessment is supported by the [TeamMates tool](https://teammatesv4.appspot.com/) .