---
layout: post
title: Rig My Roll
description: A Rogue-like Slot Machine game 
---

<!-- Example modified from [here](http://www.unexpected-vortices.com/sw/rippledoc/quick-markdown-example.html){:target="_blank"}. -->

<!-- [Rig My Roll](https://milosneptune.itch.io/rig-my-roll){:target="_blank"}
============ -->

![Rig](https://people.rit.edu/hhq8650/portfolio/rig.gif "Rig My Roll!"){: width="300" }
<!-- ![Rig](/portfolio/assets/images/rmr-ss6.png "Rig My Roll!"){: height="300" } -->

[Rig My Roll](https://milosneptune.itch.io/rig-my-roll){:target="_blank"} - Academic Project
----

### What is [Rig My Roll](https://milosneptune.itch.io/rig-my-roll){:target="_blank"}?
**Rig My Roll** is a slot machine rogue-like high-level game prototype created by a team of four people as an assignment for the IGME-106 course, **Problem Solving with Data Structures and Algorithms for Games**.

![Rig](/portfolio/assets/images/rmr-ss6.png "Rig My Roll!"){: width="300" }

There were many challenging aspects we faced when creating **Rig My Roll**. The largest being that development was constrained to only two weeks, as well as our limited use of the MonoGame framework and the framework's minimal documentation.  

#### Role: Game Designer, Developer, Project Coordinator
  * Coordinated project tasks and organized task board, assigned tasks to team members, ensured project schedule
  * Implemented logic for randomizing and efficiently manipulating slot rolls, slot machine and item usage, and loading textures from file 
  * Presented pitch to a classroom setting 
  * Maintained consistent coding standards and conventions across project and encouraged use of version control 

**Tools:** C#, MonoGame Framework, Visual Studio, Trello

**Team Size**: Four people
<!-- put some diagrams of our uml here !! -->

#### Design & Development 
It was my role to design and implement our slot machine logic. This was my first time attempting this sort of complex logic. I wanted to make sure our code was as effective as possible with my given skill level. Normally, I would have wrote something super simple, but we needed the ability to manipulate the chances of the slots in different ways. 

I spent a lot of time looking at real life slot machines and how they were coded. Eventually, I decided to write a Slot class and a Slot machine class, the Slot class holds two lists of different symbols, one constant unchanged list, and a duplicate list to be manipulated. Through multiple different methods, the duplicate list would be changed depending on what item the player has used. For example, if the user increased the chance of rolling "Symbol A," the duplicate list would randomly replace one symbol in itself with "Symbol A." 

![alt text](/portfolio/assets/images/rmr-ss4.png "Code screenshot, can be found on my github"){: width="500" }
![alt text](/portfolio/assets/images/rmr-ss1.png "Code screenshot, can be found on my github"){: width="500" }

We found this method of weighted chance to be incredibly helpful, as we could "reset" the duplicate list to the unchanged list as well as easily manipulate the list's items without losing important information. 

<!-- ![Rig](/portfolio/assets/images/rmr-ss6.png "Rig My Roll!"){: width="300" } -->
<!-- ![Rig](/portfolio/assets/images/rmr-ss5.png "Rig My Roll!"){: width="300" } -->


#### Related Links:
* [Repo](https://github.com/milosneptune/Rig-My-Roll){:target="_blank"} 
* [Design Document](https://docs.google.com/document/d/1NOynjQzR9SYnmqHZo_F6KJ1ViQqpxnBwyExbnPuPQnQ/edit?usp=sharing){:target="_blank"} 
* [Itch.io](https://milosneptune.itch.io/rig-my-roll){:target="_blank"} 
