---
layout: post
title: Introduction to SpaDES Workshop
author: Eliot McIntire, Alex Chubaty
date: August 9, 2016
comments: true
tags: [SpaDES, workshop, raster]
---

Alex Chubaty and I will be leading 2 introductory SpaDES workshops this fall. They will essentially be the same course, but one will be mid September, and the second will be in early December. 

The two workshops will be similar. We will be doing two workshops because there is immediate need for some users, but there are major travel restrictions for other users given the time frame.

### Dates: 

- Workshop 1 - Sept 14-16, 2016
- Workshop 2 - Dec 7-9, 2016 (tentative)

#### Both workshops:

**Cost: Free**

**Where: Pacific Forestry Centre, Victoria, BC**

**Approximate content (will be updated in early September):**

1.	**What is SpaDES and examples**  
    a.	Fire – Beacons  
    b.	Vegetation simulation – SpaDES-Landis  
    c.	Agent models – [Wolves](http://htmlpreview.github.io/?https://github.com/PredictiveEcology/SpaDES-modules/blob/master/modules/wolfAlps/wolfAlps.html)

2.	**Building a new module from scratch**  
    a. newModule  
    b. the event queue  
    c. simInit and the simList object  
    d. scheduleEvent  
    e. the spades function  
    f. module metadata  
    g. initializing data  
    h. visualizing  
  
3.	**Modules types**  
    a. events (e.g., Fire)  
    b. data modules (e.g., climate data downloading)  
    c. individual-based modules (e.g,. caribou)  

4.	**Experiments and replication**  
    a.	experiment function (replication, scenario creation, parameter experiments)  
    b.	supercomputers and clusters  
    c.	Pattern Oriented Modeling (POM function) for estimating unknown parameters  

5.	**Power R for speed**  
    a.	Spatial data (raster and sp packages)  
    b.	Matrices  (for fast operations on numerics)  
    c.	data.table (for fast operations on data.frames, i.e., columns of data)  

6.	**Integrating across modules**  
    a.	Building “models”, i.e,. groups of modules

7.	**Online**  
    a.	Using GitHub.com  
    b.	Using Shiny for web interfaces (still in alpha state)  
    c.	Shinyapps.io e.g., [Proof of concept](https://spades.shinyapps.io/ForestChange_ProofOfConcept/)  
    d.	Data sources  

8.	**Data to decisions**  
    a.	Building a reusable workflow
    b.	Caching
    
#### Resources:

- [SpaDES wiki](https://github.com/PredictiveEcology/SpaDES/wiki)
- [R documentation for SpaDES](http://www.rdocumentation.org/packages/SpaDES/versions/1.2.0)
- [Development release of SpaDES](https://github.com/PredictiveEcology/SpaDES/tree/development)