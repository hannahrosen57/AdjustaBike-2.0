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
    - [x] bike
    - [ ] kit
- [x] Collate a list of technologies already identified as candidates
- [ ] If time - morphological chart?
- [x] Update today's log

note: this article on [Geometry Charts](https://www.bikeexchange.co.uk/blog/bike-geometry-charts) is coming in handy when trying to quantify the requirements for the bike. I'm aiming for a sort of hybrid commuter style geometry, nothing too aggressive.

other links:

https://bike.bikegremlin.com/832/bicycle-frame-geometry/

https://www.boardmanbikes.com/gb_en/products/2256-slr-9.2.html

https://www.boardmanbikes.com/gb_en/products/2171-mtx-8.8.html

https://www.boardmanbikes.com/gb_en/products/2232-adv-9.0.html

https://www.cyclingweekly.com/group-tests/road-bike-geometry-explained-407599

the image and table below are taken from Jamie's report:
![](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/bike%20geometry.PNG?raw=true)
![](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/bike%20geometry%20values.PNG?raw=true)

A list of some possible candidates was collated and uploaded [here](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/possible%20components/component%20candidates.xlsx). The bike requirements were organised into a table and uploaded [here](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/Product%20Specs.xlsx). 

## Tuesday 11th February

- [ ] Product Specification
  - [ ] Quantify requirements
    - [ ] bike
    - [ ] kit
  - [X] Lay out in a table with demand/wish weights
    - [X] kit
- [ ] If time - morphological chart?
- [x] Supervisor meeting
- [x] Update log 

I had a Doctor's appointment and some important errands today so I didn't get as much done as usual.

## Wednesday 12th February

- [ ] Product Specification
  - [ ] Quantify requirements
    - [ ] bike
    - [ ] kit
  - [ ] Add RS, bamboo, timber, 3D printing, and anything else I think of to component candidates spreadsheet
  - [ ] Decide on morphological chart categories for bike, ie. wheels, brakes, drive, steering, interface/attachment/bearing mechanisms, links, joints, geometry, adjustment/adaptaion mechanism(s). Refer to Jamie's work, infento, other competitors, etc.
  - [ ] Add Dutch upright bike to weight data
    
### Call from The Tube and Clamp Company
11.46am, I just got off the phone with the tube and clamp company. I had to give them my contact details to download the brochure, and I was in the middle of typing up the mess below (quantifying product spec) when they called me. I was able to ask them some questions which was helpful because they don't have any prices in their brochure and it wasn't clear if it was possible to order small quantities or if it was exclusively geared towards big industrial applications. I'll type up the key points below. This is sounding pretty feasible, all in all. 

It sounds like 4m of aluminium profile would be roughly £20 and joints (which consist of two clamps bolted together) would be about £1.50 each. The tubes come in 4m lengths and they can cut them to size for 50p/cut. They have a big warehouse in France where they ship bulk orders from, but since it's a small scale project they would probably ship it from their stock in the UK. They have a courier type deal set up for the 4m tubes, but it's easier and cheaper if they're cut to length first. The joints are shipped seperately in a normal box. Lead time from knowing what parts I need until they arrive here would be about 5 to 7 days. I forgot to ask about shipping costs, maybe I'll email him to ask. Edit: he said in his email that I could expect to pay £20-30 in shipping for such small quantities.

He said the company isn't usually too keen on giving out their CAD files, despite being asked about that a lot. I said I totally understood the need to protect IP and that I could probably mock up some simplified versions to figure out which parts I need. However, he seemed to be pretty keen for me to send him a sketch or simple CAD drawing of a concept, with any other important info like the forces involved, and they could put together a SolidWorks assembly from their part files and send me the Bill of Materials and presumably assembly drawings. This service would be free of charge. This would be useful because they know their product best and can find a good combination of components, weight optimised, cost optimised, taking account of loads it needs to withstand, etc. 

#### We now interrupt your regularly scheduled programming for a brief descent into madness.
Two concerns: a) is that cheating? and b) the same parts need to be used to build multiple assemblies, and unlike timber or scaffolding tubes, it doesn't make sense to just chop a bit off the end or buy a new tube when you need to build something new with different length tubes. Unless I just buy extra as spare? So, I would likely need to iterate geometry/assembly designs until I'm happy with at least a couple, trying to make sure they share as many parts as possible, and then send them two or three different concepts. Or, get them on board with the kit concept early on and use their expertise in the decision process, with the risk that I might not choose to take their product forward as the final concept. Again, is that cheating? The guy I spoke to said he'd email me so I can contact him when I've nailed down my concept a bit more, and I also asked him to type up a brief summary of everything we'd discussed. I thought I'd also type this up before I forget anything. 

Also, a major design consideration is whether joints allow adjustable length without cutting the tubes, and if that makes the transverse bulky if they need to be side by side rather than inline. Can we use angular adjustment to adjust the length by 'folding' links in the middle? Or telescope? Or design the geometries so they mostly use the same lengths and adjust with a different mechanism? Is it possible to predict that different lengths will not be needed for geometries that have not been designed yet? Can enough flexibility be possible just by working around set lengths? It works for lego and meccano, if you think about it they're not very adjustable, they just have discrete sizes of building blocks which can be combined. But they're not dealing with trigonometry. But, the bike frame doesn't necessarily need to look like the standard 'triangle' shape. It could be like a brompton bike, relying on cantilevers. That would make getting the right lengths easier, but would the bolt-together joints be strong enough for a cantilever? Will the extra bending strength necessry in the links make it unneccesarily heavy? Will relying on discrete building blocks mean that a large quantity of components are needed, many of which aren't used at a given time? That would defeat the purpose of trying to reduce cost and storage space. It might be possible to adjust the 'discrete' lengths to match your height and only order those exact 'building blocks'. But then there's the original problem of needing different exact lengths when you decide to build a tricycle. And then is it truly a flexible kit? Or just a DIY project? If you have to order new parts for each different geometry I don't think it fulfills the project brief. 

Ahh these are all things which I'll try to decide with my morphological chart after I sort the project spec, but they're all interconnected and it's hard to separate them because I feel like the choice of technology/product/component will influence which features would work best, but the required features also influennce which technology would work best. Plus, maybe a combination of different technologies would work best! That adds tonnes of different variables! Not to mention all the different combinations of wheels, steering, etc, and their attachment mechanisms! How do I solve this when it's so motherforking recursive and complex? 

![](https://i.pinimg.com/originals/fb/56/ce/fb56ce7eada9734afd049392e4c92264.jpg)

Okay. It's gonna be okay. We have a system to work through this mess. It's not perfect, and I might have to iterate a few times, and maybe I'll miss things and I won't find the best solution. But maybe there isn's a best solution. But we'll probably end up with a good solution. Maybe there will be another way I could have done it, but that's pretty much always the case. I'm on the right track, I'm trying to make this messy process a bit more methodical. I just have to keep going and cross each bridge when I come to it. And hey, maybe certain design decisions don't need to be completely justified, because exploring every single possible option would be impossible. It's more important that I get something that works. Just start with something. Whoever's working on this next can improve on it. So use the tables and matrices and charts as far as is helpful, and justify the foundation and the broad strokes and use it to find options. And then just - give it a go. Use intuition about how best to attach the wheels or whatever. Make it work, and if it doesn't work, come back to all the other options you left on the drawing board. 

Maybe it won't be best, ideal solution. But it'll be something. Probably a pretty good something. Who knows, it might actually work. We can improve it later, or someone else can. That's not even cheating, that's what the design process is supposed to be. It's iterative. That's half the point of making this open source, so someone can look at this and see what happens if you try it a different way. It's not like I'm gonna make design decisions completely arbitrarily, I'll have some justification. Even if it's just time constraints - sometimes you have three equally good options and you just have to pick one and try it. I mean think about how many variations on a theme there are on the market right now. There's more than one way to skin a bicycle. Okay. It's gonna be okay. You're thinking far too much about this, get a freaking grip.

**actual useful thought:** I was going to go through the whole design synthesis process and then, once I had the final concept, try and source components to build it. This is the usual way of doing things with a normal design project. But, with this one, the design is really built around and influenced by the components that I'll be using. So, I think it makes more sense to (after finishing the product specs) research the possible technology candidates, in the broad strokes since there are so many different product lines within each company, write some notes on them, including some of the more tangible, simple requirements like weight per metre, and then base the morphologocal chart on these different technologies. Then I can filter out the duds and build and evaluate initial concepts around the components which are available (ie. 'steel scaffolding tubes to fit interclamp' and 'aluminium graphit tubes from the tube and clamp company' instead of just 'tubes' as options in the 'links' category), and combine them if beneficial, possible, and worthwhile. I can iterate if I need to by redesigning the final concept and reeveluating it until I'm happy. But at least then I can use the things I already know about the technologies/components to inform the design decisions at the concept stage. Yeah, I'm a lot happier with that process. It'll involve a bit of digging around and emailing people, since cost and info etc. isn't always readily available, but I think it'll work. See? good talk. Not a complete waste of time.

### Quantifying Product Spec Requirements
I'm feeling a bit intimidated and overwhelmed by the task of trying to quantify the requirements for the specification. I think it's because it involves a lot of interdependent steps, fact-finding, assumptions, decisions, and calculations, and because there isn't necessarily a 'right answer' or a way to check if I've done it right. And because I feel like this should be a simple task and I should have finished it already. But, to be fair, this is probably going to involve some back-of-the envelope FEA and writing up a long-winded decision process involving calculations, both of which take time, and this is the foundation for everything that I'll do later.  So, step 1, accept that this is going to take time and that's okay. Step 2, break it down. Acknowledge that a lot of assumptions will need to be made in order to calculate things, and that's okay as long as I use good margins and safety factors to find a reasonable 'worst case' design limit. It's okay if this needs to be adapted later when I have more information.

Okay, let's try to break this down a bit:
- [x] Try to find some better data on 'stack' and 'reach' for hybrid geometries, as the only example I've found that lists these quantities is giving me very strange numbers - reach values around 600mm rather than the 380mm-ish which is predicted by Jamie's report and by comparing the proportions to road bikes. In theory I could just use the road bike data, but this is not going to be a lightweight or high performance machine, so it needs to have a fairly upright riding position to be accessible as a commuter type bike.
- [x] Use hybrid geometry data to fill in stack and reach requirement ranges
- [x] Use hybrid geometry data to define a preliminary geometry for force calculation purposes. As the size of bike chosen is fairly arbitrary, choose one which would fit me. 
- [ ] Record and diagram this somehow. Simplify if necessary.
- [ ] Resaerch standards, test procedures, and safety factors for commercial bikes. To find out:
  - [ ] Weight of 'test rider'
  - [ ] Which tests does it need to pass? Static load, definitely. Shock load? Drop test? How high? How heavy? Resonant vibrations? (Probably not, at least not now, as that would require actual FEA on a computer and that's a but too in depth at this stage, but still should be noted for later.) Fatigue strength? How many cycles? 10,000? Should I model it with all the force on the bottom bracket or the seat? Both at once? Both, one at a time? Assuming that the 'test weight' is much higher than an average rider's weight, what safety factor should I use for the test weight?
  - [ ] Use the findings to fill in the relevant requirements for the bike spec (add safety factor requirement? adapt to reflect real life testing standards? Don't forget fatigue strength requirement).
  
We need to translate the bike requirements into the kit requirements. This means that we need to analyse a preliminary geometry to find the forces in the links and joints. 

- [ ] Model the bike frame as a pin-jointed structure and calculate link and joint forces. Note, we do not know the cross-sectional area or the material of the links yet, so do not try to calculate stress. We just need the forces.
  - [ ] Simplify the geometry into a 2D model. The main difference will be that the two chain stays and the two seat stays either side of the wheel will each need to be modeled by one link in the X-Y plane.
  - [ ] Decide if the fork needs to be modelled. If yes, decide on the 2D geometry. Tricky to model with pin-jointed structure. Model as constraint at a head tube joint, and then model fork seperately as a beam? 
  - [ ] On paper, diagram the bike frame as links and joints, and annotate with angles and lengths.
  - [ ] Decide on how many tests are needed. For each one, define the magnitude and direction of each load, and where on the frame they act. This may involve calculating forces using equations of motion or other methods.
  - [ ] Define the constraints.
  - [ ] Check if the structure is statically determinate. If not, adjust constraints and/or loads as necessary until it is statically determinate. Note that some unrealistic constraints might be necessary in order to solve the structure, and this is okay because we just need a good estimate. Make note of them though.
  - [ ] Draw the diagrams and solve for all the link forces for each test case, on paper.
  - [ ] Check/verify them somehow. This could be with an online tool or simplified CAD (in which case, screenshot the diagrams for the report) or just by re-doing the calculation (which might actually be quicker).
  - [ ] Decide on a suitable safety factor and calculate the design forces.
  - [ ] Decide on the level of generality at which to specify loads. On the one hand, we don't know what the final geometry will look like (it could be significantly different), and so we should give a minimum load bearing requirement that every link and joint need to meet based on the 'worst case' and safety factors. On the other hand,  
  - [ ] Use the results to fill in the 'link tension/compression' and 'joint gripping force'
- [ ] Up till now we've been treating the frame as a pin jointed structure. While some of the joints might end up being pin-jointed, some will probably be fixed, as if they were welded (except not actually welded, because I doubt Mr. Joe Everyman wants to rent a welder). We need to estimate the maximum moment on the joints, and the bending moment on the links.
  - [ ] Think about the realistic constraints that the frame will be under during testing and use. 
  - [ ] Think about which joints should be fixed. This could be all of them or none of them , depending on the design, but probably somewhere in between. Could have a couple different options.
  - [ ] Based on the pin-jointed analysis, constraints and loads, choice of fixed joints, geometry of structure, and intuition, estimate which joints will be subject to the highest torques and which links will be subjected to the highest bending moments for each test case. Do some simple calculations if necessary. Might need to make assumptions or simplify the model.
  - [ ] For each test case, model and calculate an estimate of the worst case joint torque.
  - [ ] For each test case, model and calculate an estimate of the worst case link bending moment.
  - [ ] Determine a suitable safety factor and calculate design moments.
  - [ ] Decide level of generality with which to specify the moment requirements. We don't want to overengineer smaller joints, but different geometries will have different forces and the joints have to work for all of them. Also consider that this is a ballpark 'envelope' for this specific requirement, and that there are seperate requirements for 'kit can be used to build a bike' and 'bike must support xxx kN' and ' optimise weight and cost', and that further testing will be carried out later to make sure the design is fit for purpose. We don't want to tie the design down too tightly at this stage. But, we do want to rule out things that definitely won't work so we don't have to redesign everything later.
  - [ ] Use the results to fill in the 'joint torque' and 'link bending moment' requirements.
- [ ] TYPE ALL THAT UP including diagrams and calculations!
  
Okay, that should be all the force calculations we need. Moving on.


- [ ] Do some maket research to get an idea of cost. Note we will probably not sell this, but cost is still a factor in DIY. We have an advantage in that we don't need a profit margin and don't really have any overheads, but a disadvantage in that we can't buy in bulk. Also, should we assign a cost to manufacturing and assembly time?
  - [ ] ~~Compile a list of competitors or similar products (could be more than one product from each company)~~
    ~~- toy kits ie infento~~
    ~~- cargo bike kits ie XYZ~~
    ~~- purpose-built cargo bikes, adult trikes, child-carrying bikes, tandem attachments, etc.~~
  - [ ] ~~Research and record the prices of each of them~~
  - [ ] ~~Come up with some desirable attributes like 'build quality' and 'flexibility' and give them preliminary weights based on how much the consumer values them~~
  - [ ] ~~Rate each of the competing products in each of these attributes~~
  - [ ] ~~Compute an overall 'value index' for each competing product using the attribute scores and weights~~
  - [ ] ~~Plot the cost against the value of each of the competing products on a scatter chart and show the line of best fit~~
  - [ ] ~~Adjust the weightings (and add more attributes if there are any missing) until the scatter graph shows a good correlation. Sometimes, the line of best fit is linear on a log plot when all the weights are adjusted correctly. Sometimes.~~
  - [ ] ~~Score our product on each of the attributes and calculate its value index. Use the line of best fit on the value-cost graph to find the target price for that value index.~~

Actually, scratch all of that. Just find a couple similar products on the market think about how much you'd be willing to pay for it, pick a fairly large fudge factor, and get a ballpark absolute maximum and target price. When you know what the design looks like in more detail, come back to the procedure layed out above and use it to evaluate and justify. I'll leave it here to refer to later. 

- [ ] Fill in the ballpark cost requirements

The rest of the requirements are less involved. Do some simple research and/or calculations. Don't get too bogged down in the details.
- [ ] Stopping distance
- [ ] Acceptable levels of torque due to friction in wheel, bottom bracket, and headtube bearings
- [ ] Range of motion in steering
- [ ] Max. manufacture time and assembly time
- [ ] etc.

I'm sure there will be other things but that's all I can think of right now. Argh, it's half two and I haven't eaten any lunch or done anything productive, I just wrote all that ^. Ahhhhhhhh

I found a couple other geometry charts and the numbers make more sense. Also, I went back to the first ones and I must have read the table wrong because it's actually perfectly normal. I recorded all the stack and reach data in the product spec spreadsheet. 6 bikes in total. The force calculations will use the geometry based on that of a size small cannondale quick 4. This was chosen because the style of geometry is similar to the one I am aiming for, and in theory this size would fit me. The relevant geometry chart data and diagrams is in the product spec spreadheet. The data was used to fill in requirements 4 through 8 of the bike requirements. The table above was used to give context by comparing with different types of bikes. I will upload the updated spec here.

## Thursday 13/02/2020

- [x] Record and diagram preliminary geometry. Simplify if necessary.
- [ ] Resaerch standards, test procedures, and safety factors for commercial bikes. To find out:
  - [ ] Weight of 'test rider'
  - [ ] Which tests does it need to pass? Static load, definitely. Shock load? Drop test? How high? How heavy? Resonant vibrations? (Probably not, at least not now, as that would require actual FEA on a computer and that's a but too in depth at this stage, but still should be noted for later.) Fatigue strength? How many cycles? 10,000? Should I model it with all the force on the bottom bracket or the seat? Both at once? Both, one at a time? Assuming that the 'test weight' is much higher than an average rider's weight, what safety factor should I use for the test weight?
  - [ ] Use the findings to fill in the relevant requirements for the bike spec (add safety factor requirement? adapt to reflect real life testing standards? Don't forget fatigue strength requirement).
- [x] Update  log

I've found some great information on test prcedures from the ISO 4210 standard! But it's going to take a while to wade through it all, and it has important info on the other systems as well. So I won't tick it off yet. More detail below. As for safety factors, there's always this old rule of thumb [[source]](https://www.engineeringtoolbox.com/factors-safety-fos-d_1624.html):

![](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/safety%20factors.PNG?raw=true)

So I'm thinking maybe 2ish? The test procedures are pretty rigorous, and I don't want it to be too heavy. But I also need to give people peace of mind that it's not going to fall apart even though it's not welded. Technically one would be trusting one's life to this thing. Hmm. Let's say **sf =  2 to 3** for now.

### Defining, drawing, and simplifying preliminary bicycle geometry
I went looking for a CAD programme to draw up the preliminary geometry and happened across all the fikes from Jamie's Adjustabike project. He shared the folder with me on the Fusion 360 cloud thingy. [Here's a link](https://myhub.autodesk360.com/g/all_projects/active) to the webapp.

I thought I'd just draw up a simple diamgram of the preliminary geometry, but this computer doesn't have Inventor. I tried the Fusion 360 webapp but it doesn't allow you to create drawings. After about an hour tearing my hair out wrestling with AutoCAD I think the best bet is to pack up and go find an engineering lab computer and use Inventor. It will probably save me time in the long run because I won't have to transfer the file from AutoCAD to Inventor, which can be complicated. Ugh this was supposed to be a 5 minute job.

Okay I used the geometry chart from the cannondale website to draw up a sketch of the geometry. I then made a separate sketch with simplified geometry which I'll use for the initial pin-jointed-structure force calculations. I had to make a couple changes to make sure it was a structure rather than a linkage (ie not going to flop over), and to make it slightly easier to analyse. I'm okay with that because this is only supposed to be a ballpark figure. I don't even know what the final geometry will look like, it might be totally different. I was originally going to just do the calculations based on something really simple like a pin jointed equilateral triangle, just to get a general idea of the forces, but I figured I might as well use an actual bike geometry since I've got the info already. Probably made life more difficult than it needed to be, it took ages to get all the dimensions dialled in. The geo chart is just rounded up to the nearest mm, and without that extra precision nothing matches up. Oh well, on the up side I've got a bit of a better idea of the kind of precision (or adjustability) I'm going to need when building this thing. And it'll help when deciding which angles of joints I'll need, etc. I'll put some images in below.

*below: geo chart from cannondale website for the quick 4. values shown are for the size small.*

ref| dimension                    | value
---|------------------------------|---------
A  | Seat Tube Length	            | 40cm
B  | Top Tube Length	            | 55.7cm
D  | Head Tube Angle	            | 70.0°
E1 | Seat Tube Angle Effective  	| 73.0°
F  | Standover	                  | 69cm
G  | Head Tube Length	            | 13.4cm
H  | Wheelbase	                  | 105.3cm
I  | Front Center	                | 62.7cm
J  | Chain Stay Length	          | 43.5cm
K  | Bottom Bracket Drop	        | 6.8cm
L  | Estimated BB Height	        | 27.7cm
M  | Fork Rake	                  | 5.5cm
N  | Trail	                      | 6.7cm
O  | Stack	                      | 55.4cm
P  | Reach	                      | 38.8cm

![](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/cannondale%20geo%20chart.png?raw=true) | ![](https://embed.widencdn.net/img/dorelrl/omccgq1yg1/2000px@1x/C20_C31400M_Quick_4_GRA_PD.png) 
----------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------
*above: cannondale geo chart reference diagram*                                                                 | *above: cannondale quick 4*

Click the images below to see them in more detail.

![](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/prelim%20bike%20geo.png?raw=true) | ![](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/prelim%20bike%20geoN.png?raw=true)
-----------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------
*quick 4 geometry values*                                                                                  | *quick 4 geometry names*
![](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/prelim%20bike%20geo1.png?raw=true)| ![](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/prelim%20bike%20geo2.png?raw=true)
*quick 4 geometry and simplified geometry superimposed*                                                    | *simplified geometry annotated with dimensions*

### ISO 4210 Cycles — Safety requirements for bicycles
I found a very useful ISO standard on testing procedures for bicycles. I was able to download it for free from the BSOL database with my library login, which is nice, because they're usually pretty expensive. It is divided into 9 parts as follows:

- Part 1: Terms and definitions
- Part 2: Requirements for city and trekking, young adult, mountain and racing bicycles
- Part 3: Common test methods
- Part 4: Braking test methods
- Part 5: Steering test methods
- Part 6: Frame and fork test methods
- Part 7: Wheels and rim test methods
- Part 8: Pedals and drive system test methods
- Part 9: Saddles and seat-post test methods

Parts 1 and 2 say that: 

*"This part of ISO 4210 does not apply to specialized types of bicycle such as delivery bicycles, recumbent
bicycles, tandems, BMX bicycles, and bicycles designed and equipped for use in severe applications such
as sanctioned competition events, stunting, or aerobatic manoeuvres."* 

However, Parts 3 through 9 no not mention this caveat, even though they reference Parts 1 and 2. I think I'm going to have to read through this whole thing and make notes on it. Then I can decide which parts I need to implement in my design spec. I am focussing on the frame, and because this project is geared towards DIY the burden is partly on the consumer, but I think it's still a good idea to read through the sections on braking, steering, etc. It's a pretty lengthy, dry set of documents, and it goes into detail about how to test all kinds of things (ie mudguards, rubber handlebar grips). It'll take some time, and I don't expect I'll put it into practice with as much rigour as a normal bicycle manufacturer, but there might be useful/important things like guideline stopping distances and bending forces used in tests. And it'll be a good way to check if I've missed any major requirments in my spec. I anticipate the sections on 'Frame and Fork Test Methods' and 'Common Test Methods' will be the most useful. I'll upload the PDFs here in the 'clutter' folder.

okay so here's what I did:
- skim through the whole thing
- part 6 seemed the most relevant so I read through that in a bit more detail. There's a lot of helpful info!
- there's a static test, some drop tests, and fatigue testing for the frame. The parameters, procedure, and setup were given but I couldn't see any requirements for passing/failing the test. I found a couple similar standards which did specify the requirements, and then realised the requirements were all in part 2 (duh)
- I made a little plan:
  - [ ] read through the 9 parts. As I go, write down anything relevant to AdjustaBike 2.0, including section refs
    - [x] 1
    - [ ] 2 (started!)
    - [ ] 3
    - [ ] 4
    - [ ] 5
    - [ ] 6
    - [ ] 7
    - [ ] 8
    - [ ] 9
  - [ ] Review notes and decide if I need to add to or adapt the requirements in my product specification for the bike
  - [ ] If necessary, translate these new bike requirements into kit requirements
  - [ ] Quantify all the relevant bike requirements ie steering angle +/- 60 degrees
  - [ ] Quantify kit requirements as planned above
- I read through and took notes on Part 1 and a good chunk of Par 2. this is going to take a while. A lot of detailed, relevant stuff.
- For the drop test, I need a way to approximate the impact force. I could use conservation of momentum, but I don't know how long it'll take to decelerate and the time interval is important. [This article](https://www.wired.com/2014/07/how-do-you-estimate-impact-force/) makes a good point about using a distance instead of a time interval by using the work-energy principle. I can get the maximum distance interval (extension) from the test requirements in ISO 4210. Also, [here's](https://www.youtube.com/watch?v=32k96ahyB2g&feature=emb_title) a video of a wooden bike undergoing the drop test. Could use it to check if the time interval calculated is in the right order of magnitude.

It feels like I've made no progress and I don't know if that's because my expectations are too high or because I'm actually behind and need to hurry up.

To be fair, when I planned this all out I sort of skipped past product specification and conceptual design, and just assumed I would jump straight in the deep and of embodiment and detaildesign, and get a prototype going as soon as possible. I still want to get that prototype going as soon as possible, but when I get the chance I want to rewrite my timescale to put more emphasis on the conceptual stage. If I'm not throurough and rigorous with this part things will go wrong later. Here's hoping the embodiment design won't take as long as this so I can start building the thing! 

![](https://ars.els-cdn.com/content/image/3-s2.0-B9780128025079000027-f02-15-9780128025079.jpg)

## Friday 14th February

Late night last night because I had a bit of momentum going, paying for it today with major inertia. Focussing on taking notes on the standard and then I'll come in on Sunday and try to make some more progress with the spec.

- [ ] read through the 9 parts. As I go, write down anything relevant to AdjustaBike 2.0, including section refs
  - [ ] 2 
  - [ ] 3
  - [ ] 4
  - [ ] 5
  - [ ] 6
  - [ ] 7
  - [ ] 8
  - [ ] 9
  
  ## Sunday 16th February
  
- [ ] Print and annotate Jamie's Design Specification. Note anything I'd like to add to mine (they'll be a bit different since we're designing different products)
- [ ] Use Jamie's categories as inspiration to add some more structure to my Product Specifications
- [ ] Choose which requirements from ISO 4210 to add to the spec
  - [ ] Could write something like 'frame should comply to ISO 4210; tests may be carried out with FEA if physical tests are impractical'
  - [ ] Still need to analyse forces in order to find the maximum link and joint forces for the kit specification, and for design insight
  - [ ] Could write seperate document summarising estimated forces from tests and the requirements for maximum permissable displacement etc
- [ ] Referring to ISO 4210 notes and Jamie's spec, add and/or rewrite requirements to bike specification, using placeholders for quantities
- [ ] Fill in as many bike spec quantities as possible
- [ ] Continue with force calculations as outlined above

I know that's a lot to aim for in one day but I can continue on Monday!

[jump to top](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/ProjectLog.md#project-log)

##### {end link}
