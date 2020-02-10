# Project Log
This document is intended to be an ongoing record of the progress of the AdjustaBike 2.0 project. The project is building on the Adjustabike, which was an adjustable DIY bicycle kit concept developed by a previous Final Year student, Jamie. The aim is to accomplish the same goal, but to make it as accessible to the lay person as possible by using mostly off-the-shelf parts and simple manufacturing methods, and to ensure that the kit is truly open-source by documenting it thoroughly.

[jump to end](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/ProjectLog.md#end-link)

## Friday 1st November (retro)
### Introductory Meeting Minutes
- Review existing work and concepts
- How to divide work between Alex and me?
  - test & optimise / design & develop
  - computational / experimental
  - different joints?
  - different directions entirely?
- Parts to manufacture - drawings
  - get in touch with Jamie?
- Timescale? need to establish the broad strokes, especially of assesments
- Literature Review (what to include)
- Technicians (need to attend tech surgery)
  - machining
  - testing - introm machines?
- To consider when designing and evaluating bike:
  - Vibrations
  - Maximum/typical load
  - Mass/weight
  - Ergonomics
    - Riding position
    - Knee clearance
    - Transmitted forces
  - Cost
  - Ease of assembly

To do before next meeting on Wednesday 6th:
- [x] Read through Jamie's report thoroughly
- [x] Have a good think about the best way to divide the work
- [x] Hash out rough outline of deadlines
- [x] Get an idea of what's involved in each handin
- [x] Review examples of past PSPs

## Tuesday 5th November (retro)
- Reviewed the outline of the timeline and hand-ins given in the 'FYP Instructions' booklet
- Read through and highlighted Jamie's report. It should be helpful for writing the PSP, especially the lit review
- Brainstormed (see below):
  - Directions the project could be taken, to help decide how to divide the work with Alex
  - Thoughts/observations after reading Jamie's report
  
![alt text](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/directions%20to%20explore.png?raw=true "directions to explore")

![alt text](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/thoughts%20on%20Jamie's%20report.png?raw=true "thoughts on Jamie's Report")


## Wednesday 6th November (retro)
### Project Brief Meeting
Alex and I had both taken the past few days to familiarise ourselves with the project. After reviewing our thoughts and findings, we agreed that Alex would take the existing designs and improve them to make them more manufacturable, and I would take the project in a different direction by attempting to make it as accessible to the lay person as possible, and focussing on the open source aspect. I worked with Jeremy (who is my supervisor) to figure out what I'll be trying to do in a bit more detail. Jeremy then summarised this in 'Project Brief' documents (one for each of Alex and myself) and gave us the chance to make any changes. We all seemed to be on the same page, because neither of us needed to edit the proposed briefs. I have uploaded it here. This will be very helpful when writing the work packages and aims of the PSP.

## Wednesday 13th November (retro)
### Third FYP Meeting
This meeting was mostly spent discussing the logistics of open source hardware.

open source:
- allow future FYP students (and anyone else) to understand and continue work
- official definition is that there should be sufficient documentation and access to editable files that anyone should be able to:
  - make
  - study
  - develop
  - distribute
- you could almost say there are two products/outcomes, the bike kit and the documentation
- use of GitHub for version control, documentation, and sharing
  - could use markdown directly for project log
  - or, could keep uploading new versions of a word document so it's easier to write the report
- Design log?
- Instruction booklet?
  - photographic documentation of assembly process?
  - technical drawings?
  - research best practice
- The developement and design decisions need to be documented as well as the final product
- both raw and viewable CAD files should be uploaded to GitHub

## Writing the Project Scoping and Planning Report (retro)
The final PSP Report and the feedback for it will be uploaded here.
### To Do List
- Prep:
  - [x] read assignment brief, especially mark scheme
  - [x] create plan of action
  - [x] read example PSPs
- Scoping:
  - [x] go over project briedf and meeting minutes
  - [x] draft aims and objectives
  - [x] draft Work Plan including deliverables and prototypes
  - [x] draft introduction and background
- Planning
  - [x] lay out deliverable timescale
  - [x] assess time needed for each project phase
  - [x] draft overall timescale
  - [x] carry out contingency planning i.e. in case Phase 1 fails, what will Phase 2 be?
- Lit Review
  - [x] decide what to cover
  - [x] compile resources
  - [x] read them!
  - [x] draft lit review
- Report
  - [x] revise drafts
  - [x] summary
  - [x] references
- Misc.
  - [x] title page
  - [x] check figure references all match up correctly
  - [x] fill out the risk assessment
  - [x] hand-ins (paper and moodle)

### Aims and Objectives (draft)
#### Overarching Aim
Design a kit with which a lay person can easily and non-destrucively assemble a bicycle with a geometry of their choosing, ensuring that the ratio of off-the-shelf parts to custom parts is as high as possible in the interest of accessibility to the lay person.
#### Objectives
1) Investigate available off-the-shelf technologies and recommend which would be the most suitable to include in the kit as the tubes, joints, and interfaces of the bicycle frame. based on a set of criteria.
1) Develop a simplified modelling mechanism to test combinations of the recommended components and use it to:
   1) Demonstrate the feasability of creating different geometries
   1) Make a recommendation on which lengths, angles, and quantities to include in the kit
1) Source the components and build a physical prototype of one or more of the geometries
1) Document the kit thoroughly so that any lay person is able to replicate the design

### Literature Review
- Jamie's Report
- Different solutions to similar problems
- Geometries, components, and Engineering of bicycles
- Consumer behaviour regarding customisable products
- Open source philosophy and licensing
- Assembly instructions best practice

## Monday 3rd February
### Julian House Bike Workshop
Julian House Bike Workshop is a charitable enterprise in Bath which accepts donated bikes, fixes them up, and sells them, using the profits to help the homeless community. They also provide training and employment for homeless people, and run workshops where members of the public can learn how to maintain their own bikes.

Before I start building a wacky DIY bike, I'll need to know where I'm starting from. I will also need a good understanding of the various ways in which the other components attach to and interface with the frame, so that I can design the frame accordingly. To these ends, I paid them a visit. The gentleman working there was very helpful and told me to pop back anytime. Here is a rough summary of what I found out:

* To maybe visit/contact:
  * There is a DIY bike show called [Bespoked](http://www.bespoked.cc/) which is awesome and would be worth a visit, even though it's in May. It's also in Bristol though, which is good, because it could have been anywhere in Europe.
  * The Bicycle Academy in Frome has various courses to teach people how to build a bike frame from scratch (by welding). They can be a bit expensive, though. They also make and sell their own jigs, which are often cheaper than alternatives.
  * Julian House has truckloads of scrap bikes that I could have for free and take apart, cut up, or canabalise for parts. They're also always happy to answer questions about bike contruction and maintenance.
* To look into:
  * Bike fitting jigs are contraptions designed to have a totally adjustable geometry (wheelbase, rake, etc.) to allow riders to find a geometry suitable for them.
  * Folding bikes such as the [Fubifixie](https://fubifixie.com/) and [split frame](https://splitbikes.com/products/split-frame-kit) [bikes](https://splitbikes.com/products/split-frame-kit), which have a threaded tube joining the two halves of the top tube together
  * DIY fork or outsource fork?
* To know:
  * The head tube and bottom bracket are usually mass produced and bought in
  * The seatpost comes in lots of different sizes to fit the seat tube. Tolerances are important
  * Dropouts are usually made to order as they are so specific and tightly toleranced
  * Chain line/alignment should be considered
  * Distance between dropouts is important. Needs to fit gears (if applicable) and wheel
  * For fixies, the chain tension needs to be set correctly. The back wheel is on sliders and can be clamped in place with a threaded nut. Freewheel mechanism?
  * Every bike has a geometry sheet with key distances and angles
  
  Bike frame anatomy, for reference:  
![alt text](https://res.cloudinary.com/engineering-com/image/upload/w_640,h_640,c_limit,q_auto,f_auto/image003_c20pa6.jpg "bike frame anatomy")

### Other
- [ ] email Jeremy and Alex to setup meeting
- [ ] message people about setting up regular breakfast meetups for structure and accountability
- [x] start project log
- [x] go talk to Julian House
- [ ] assign new timescale to tasklist from PSP, and plan this week in more detail

## Tuesday 4th February
- [x] Set up Breakfast Club
- [ ] Email Alex and Jeremy to set up meeting
- [ ] Assign new timescale
- [ ] Update Project Log

Didn't get much done today. Struggling with stucture and knowing where to start. Hopefully the breakfast club and planning will help with that.

## Wednesday 5th February
- [x] Research mechanical design synthesis and plan how to develop criteria
- [x] Got in touch with Alex RE meeting, and he's already emailed Jeremy
- [x] Assigned new timescale to tasklist and uploaded here
- [ ] Upload and type up backlog of meeting minutes, reports, etc, to GitHub (started)
- [x] Figure out a system for weekly planning and plan next week
- [x] Update Project Log for yesterday
- [x] Update Project Log for today
- [ ] Emails
- [x] Read through presentation from Monday

- I will plan each week on a paper calendar to allow for easy adjustment. Initially I will just print these out, but I'll try to buy a pad them when I see one.
- With regards to researching mechanical design synthesis, the following books were consulted:
  - MECHANICAL DESIGN SYNTHESIS by RC Johnson
  - MECHANICAL DESIGN by Peter RN Childs
  - SHIGLEY'S MECHANICAL ENGINEERING DESIGN by Joseph Edward Shigley et. al
  - ENGINEERING DESIGN METHODS by Nigel Cross
  - ENGINEERING DESIGN: THE CONCEPTUAL STAGE by MJ French
- The volume by Nigel Cross was selected to be used as reference moving forward as it is the most relevant, easy to understand, and has good worked examples. The methods described are also familiar from 2nd year design, so it is likely the same book the lecturer referenced.
- The process of designing criteria for evaluating the technologies will be:
  - product design specification (fig 40, page 83)
  - 'house of quality'/interaction matrix, optional (fig 44 page 99, fig 45 page 100, fig 48 page 103)
  - morph chart (fig 50, 51 page 111)
  - initial concepts from morph chart
  - weighted objectives to evaluate initial concepts
  - choose or design final concept, and sketch
  
## Thursday 6th February
Captain's log: Phew! This log is finally up to date! That took so much longer than I expected! Now I'm behind on the design synthesis.

- [x] Retroactively type up meeting minutes, etc. from before this project log was sterted
- [x] Today's log entry
- [ ] Product Specification
- [ ] Interaction matrix?
- [ ] Morphological Chart
- [ ] Initial Concepts
- [ ] Weighted Objectives / Pugh Matrix
- [ ] Final Concept
- [ ] Criteria

Maybe I'm trying to do too much in one day with all this conceptual design stuff. It's probably going to form a significant portion of the report after all. But I want to leave plenty of time for prototyping and developing things. Well, I'll see how I get on tomorrow and then update the timescale. I'm tempted to stay late and at least get the Spec done but it's already almost 1900 and I have a lot of Life Admin to do. Tomorrow, then. 

Rosen out.

## Friday 7th February

- [ ] Product Specification
  - [x] Brush up with the textbook
  - [x] Consider Levels of generality
  - [x] Determine level of generality at which to operate
  - [x] Brainstorm requirements
  - [ ] Quantify requirements
  - [ ] Lay out in a table with demand/wish weights
- [x] Update log

The challenge with creating a product specification is that it must be specific enough to sufficiently restrict and evaluate the design, but general enough that it does not exclude potential solutions. For example, both the [Wishbone Design 3-in-1 Balance Bike](https://www.kidly.co.uk/products/wishbone-design-studio/3-in-1-balance-bike/8080?gclid=EAIaIQobChMI5Ymsn9rG5wIVTbDtCh3XIwTxEAQYASABEgJMIPD_BwE) (top row below) and the [Infento Explorer Kit](https://www.infentorides.com/product/explorer-kit/) (bottom row below) could arguably fullfill the same brief and product specification, just in very different ways. The product specification would not be able to specify material, fixing mechanisms, or even the general structure, as the balance bike uses curved wooden panels bolted together, while the infento kit uses aluminium 'rod' elements connected with moulded plastic joints.

[BalBike1]: https://kidlycatalogue.blob.core.windows.net/products/8080/product-images/neutral-wooden-1/wishbone-design-studio-3-in-1-balance-bike-neutral-wooden-1920x760_03.jpg "Balance Bike 1"

[BalBike2]: https://kidlycatalogue.blob.core.windows.net/products/8080/product-images/neutral-wooden-1/wishbone-design-studio-3-in-1-balance-bike-neutral-wooden-1920x760_04.jpg "Balance Bike 2"

[BalBike3]: https://kidlycatalogue.blob.core.windows.net/products/8080/product-images/neutral-wooden-1/wishbone-design-studio-3-in-1-balance-bike-neutral-wooden-1920x760_02.jpg "Balance Bike 3"

[Infento1]: https://www.infentorides.com/wp-content/uploads/2018/10/InfentoBALANCER-G2-PrspFront-690x460.png "Infento 1"

[Infento2]: https://www.infentorides.com/wp-content/uploads/2018/10/infentoSTREAMER-PrspFront-690x460.png "Infento 2"

[Infento3]: https://www.infentorides.com/wp-content/uploads/2018/10/infentoRIDER-G2-PrspFront-690x460.png "Infento 3"

![][BalBike1]   |![][BalBike2]   |![][BalBike3]
:--------------:|:--------------:|:---------------:
![][Infento1]   |![][Infento2]   |![][Infento3]

I've decided it's worth taking the extra time to do this thoroughly. It's all based on legitimate engineering principles which I can write up in my report, and it'll help avoid walking into the trap of just assuming the first idea is the best idea. Who knows, I might find some new ways of doing things. And if I don't at least the first idea will be fleshed out and justified. 

It should be noted that, because of the nature of the product, it can be difficult to separate the requirements for the kit itself from the requirements of the bike assembly and other assemblies. To address this, a set of requirements will be determined for the bike assembly, and these will be 'translated' into kit requirements. The geometries of the other assemblies are not yet known, so there will be a kit requirements that at least two geometries must be possible. Unless otherwise specified, mentions of requirements, specifications, and the like are referring to those of the kit and not the assemblies thereof. 

The levels of generality were considered, and are summarised in the table below:

level of generality    | examples
-----------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
product alternatives   | **bicycle/tricycle kit**; skateboard/rollerskate kit; welded bicyle frame with bolt-on cargo carrier, child seat, tandem attachment, sidecar, trailer, and training wheels
pruduct types          | to be manufactured and sold by distributor; **to be built by the consumer with simple manufacturing and readily available parts**; consisting of panels; **consisting of linear elements and connectors**
product features       | materials; type of linear elements; type of connectors, lengths, angles, and quantities to include in kit; type of wheels, brakes, drive, etc.; method of attaching wheels, brakes, drive, etc.

We already know which product alternative and product type we want (shown in bold). The 'linear elements' structure was selected because it would give a greater degree of flexibility for the wide range of geometries that we are aiming for, and allow for greater creativity while the user is assembling the kit, more akin to lego or meccano than flatpack furniture. Hence, the design synthesis will take place at the 'product features' level.

The requirements for the bike and then the kit were brainstormed. The resulting mindmaps are shown below:
![](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/bike%20requirements.png?raw=true)


The bike requirements were fed into the kit requirements.


![](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/kit%20requirements.png?raw=true)

## Monday 10th February
- [x] Update Friday's log in more detail
  - [x] type up decisions and findings
  - [x] type up mindmaps with mindgenius
  - [x] upload and insert into log
- [x] Email RE meeting tomorrow
- [ ] Product Specification
  - [ ] Quantify requirements
    - [ ] bike
    - [ ] kit
  - [ ] Lay out in a table with demand/wish weights
    - [ ] bike
    - [ ] kit
- [ ] Collate a list of technologies already identified as candidates
- [ ] If time - morphological chart?
- [ ] Update today's log

[jump to top](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/ProjectLog.md#project-log)

##### {end link}
