# Project Log
This document is intended to be an ongoing record of the progress of the AdjustaBike 2.0 project. The project is building on the Adjustabike, which was an adjustable DIY bicycle kit concept developed by a previous Final Year student, Jamie. The aim is to accomplish the same goal, but to make it as accessible to the lay person as possible by using mostly off-the-shelf parts and simple manufacturing methods, and to ensure that the kit is truly open-source by documenting it thoroughly.

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
- Brainstormed:
  - Directions the project could be taken, to help decide how to divide the work with Alex
  - Thoughts/observations evoked by Jamie's report
Will upload these brainstorms once I've typed them up.

## Wednesday 6th November (retro)
### Project Brief Meeting
Alex and I had both taken the past few days to familiarise ourselves with the project. After reviewing our thoughts and findings, we agreed that Alex would take the existing designs and improve them to make them more manufacturable, and I would take the project in a different direction by attempting to make it as accessible to the lay person as possible, and focussing on the open source aspect. I worked with Jerome (who is my supervisor) to figure out what I'll be trying to do in a bit more detail. Jerome then summarised this in 'Project Brief' documents (one for each of Alex and myself) and gave us the chance to make any changes. We all seemed to be on the same page, because neither of us needed to edit the proposed briefs. I have uploaded it here. This will be very helpful when writing the work packages and aims of the PSP.

# Wednesday 13th November
## Third FYP Meeting
This meeting was mostly spent discussing the logistics of open source hardware.

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
- [ ] email Jerome and Alex to setup meeting
- [ ] message people about setting up regular breakfast meetups for structure and accountability
- [x] start project log
- [x] go talk to Julian House
- [ ] assign new timescale to tasklist from PSP, and plan this week in more detail

## Tuesday 4th February
- [x] Set up Breakfast Club
- [ ] Email Alex and Jerome to set up meeting
- [ ] Assign new timescale
- [ ] Update Project Log

Didn't get much done today. Struggling with stucture and knowing where to start. Hopefully the breakfast club and planning will help with that.

## Wednesday 5th February
- [x] Research mechanical design synthesis and plan how to develop criteria
- [x] Got in touch with Alex RE meeting, and he's already emailed Jerome
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



