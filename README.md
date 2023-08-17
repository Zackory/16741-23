# 16-741: Mechanics of Manipulation (Fall 2022)

## Course Info

#### [Syllabus](https://docs.google.com/document/d/1AxfxFss_p_9C3MvgZCJwqjbkDO-DgOZ4cyRn7IIoXF8/edit?usp=sharing)  

**Time**: Monday & Wednesday 11:50 AM - 1:10 PM  
**Location**: NSH 3002  
**Instructor**: [Zackory Erickson](https://zackory.com)  
**Office Hours**: Wednesday 1:10 - 2:00 PM  

---

## Course Description

Mechanics of Manipulation is a graduate level course that dives into the fundamentals of robotic manipulation. Through this course you will learn the kinematics, statics, and dynamics of robotic manipulators as they interact with the world to accomplish tasks. You will gain experience with the intelligent use of kinematic constraint, gravity, and frictional forces. Additional topics include rigid body mechanics, automatic planning based on mechanics, deformable manipulation, and simulation of dynamic manipulation. Applications of robotic manipulation are drawn from physical human-robot interaction, manufacturing, and other domains.

## Textbook

Mechanics of Robotic Manipulation, by Matthew T. Mason. MIT Press, 2001.  
You can reach the online version of the textbook [here](http://cognet.mit.edu/library/books/view?isbn=0262133962).  
[Errata page](https://www.cs.cmu.edu/afs/cs/academic/class/16741-s07/www/Errata.txt)

## Additional Resources
[Toward Robotic Manipulation](https://www.cs.cmu.edu/afs/cs/academic/class/16741-s07/www/Mason2018.pdf). Matthew T. Mason. _Annual Review of Control, Robotics, and Autonomous Systems_, 2018.

["Introduction to Modern Robotics: Mechanics, Planning, and Control"](http://hades.mech.northwestern.edu/index.php/LynchAndPark), by Kevin Lynch and Frank Park. Cambridge University Press, 2017.

## Course Project
Each student must do a course project. This project is due by the end of the semester. The project will begin with a proposal, which should be a page or less. It should clearly describe what you intend to do. Students should expect to spend from 20 to 40 hours on the project. Course project reports will be due the 2nd to last week of the semester. The final report will be in IEEE format and should detail your project motivation, methodology, implementation, and results. You will also be given the option to upload a video to accompany your report (optional, but can be very helpful if your work is visual, and most robotics applications are quite visual). Projects may be a small manipulation problem to which you will apply some techniques learned in class, some extension or variation of a technique learned in class, or a review and implementation of a research paper related to the class material.

Experimental projects are encouraged, using any accessible robotic equipment. If you are interested in using a robotic arm but do not have access to one, please contact me. We can get you access to the AI Maker Space on campus, which has several robotic manipulators you can use. Experimental projects can be time-consuming, and if you choose this option the 20-40 hour guideline above does not apply.

Team projects are also fine, with up to 2 students.

Your project may be related to your outside research project or another class project, but should be clearly separate from it.

How do you find a good topic? Life is full of manipulation problems, most of which have never been studied. Or if you want to view locomotion as auto-manipulation, you can study a locomotion problem. Cooking, cleaning, origami are all sources of numerous different manipulation techniques. Games are also good sources. Paper football, tiddly-winks, curling, bowling, shuffleboard, horseshoes, eraser wars, are all manipulation problems in competitive settings. Every such application gives rise to numerous little research problems, when you look at it carefully enough.

If you have some ideas but could use some help focusing on a clearly defined manageable problem, I'd be glad to discuss it with you.

1. Here are some titles of recent projects, to give you some ideas of suitable topics:
    * Data-driven approach to object centric hand-grasp classification
    * Study of human writing process
    * Stir-frying
    * Touch based exploration of object inertial properties for grasping
    * Dynamic modeling and control of push-roll locomotion
    * Coordinated manipulation
    * RoboCup SSL non-kicker manipulation
    * Hand kinematics of piano playing
    * Contact force optimization for trunk stabilization in snake monster (Hexapod)
    * Design a fully automated stair climbing robot luggage
    * 3D object shape, position and trajectory estimation for manipulation
    * Object pose estimation from visual and tactile sensors
    * Drum master
    * Prehensile analysis using first-person video
    * Manipulating moving objects
    * Manipulating buttons, zippers, or other elements that require fine-motor control
    * Manipulation of cloth
    * Pouring liquid or manipulating deformable materials (such as dough)
    * Using chopsticks
2. Here is a proposal to give you an idea of the expected level of detail and organization:

    > Title: Pouring liquids  
    > Team: Moe, Curly
    > 
    > We have seen some videos of robots pouring liquids, but they do not look as good as people pouring liquids, for example:  
    > (A video of a human pouring)  
    > (A video of a robot pouring)
    > 
    > It is obvious the person is better, but not obvious exactly why. What is the objective that should be optimized? To explore that, we will devise a very simple two-dimensional simulator that pours liquid from one container into another. The pouring motion will be represented as a path in the container configuration space interpolating through a set of control points. We will formulate several different objective functions, and optimize the choice of control points for each objective, and then compare the outcomes.
    > 
    > The objectives we will explore are:
    > * minimum time to fill the receptacle
    > * least spillage within a given time
    > * (and some others)
    > 
    > This project is close to my research with Professor Groucho, but that work is focused entirely on inviscid beverages, and this project will focus on molasses.

3. Here are a few final project samples from Fall 2016 (not in IEEE format): [Sample 1](https://www.cs.cmu.edu/afs/cs/academic/class/16741-s07/www/sample_projects/yifanh_project.pdf), [Sample 2](https://www.cs.cmu.edu/afs/cs/academic/class/16741-s07/www/sample_projects/spurushw_report.pdf)


## Credit

This course was originally developed by [Prof. Matthew Mason](https://www.ri.cmu.edu/ri-faculty/matthew-t-mason/), which he taught for over 30 years at CMU.
