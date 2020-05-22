# Design of an Open Source, Low Cost, DIY Cycle Kit
This project was undertaken to investigate the feasibility of an open source, low cost, DIY cycle kit. I have succeeded in developing a design for a bicycle frame constructed from handrail clamps, and documented the design so that anyone can continue the work or build a prototype. The design can be customised by the user, and sample geometries were included in the assembly drawings. FEA was used to analyse the design, and the bicycle frame was optimised in response to the results. The final design weighs approximately 8.4kg and costs approximately £276 for the frame alone. Further work could include building and testing prototypes, further FEA analysis, espescially focusing on the bottom bracket clamp in dynamic loads, and designing other geometries using the same components such as a cargo bike or recumbent tricycle.

You are free to copy, distribute, and make changes to these designs. If you use these designs for your own project, please give credit to Hannah Rosen, link back here, and publish any new documentation in line with Open Source Hardware principles. Thanks.

Quick Links:

- [poster](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/poster.pdf)
- [final presentation](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/Presentation2.pdf)
- [preliminary presentation](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/Presentation1.pdf)
- [final report](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/report/final%20report.pdf)
- [STL files and 3D PDFs of assemblies](https://github.com/hannahrosen57/AdjustaBike-2.0/tree/master/CAD/exportedCAD)
- [Revision 1 Bike Frame Assembly Drawing](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/CAD/bike.pdf)
- [Revision 2 Bike Frame Assembly Drawing](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/CAD/LW%20bike%2010.pdf)
- [seatpost link part drawing](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/CAD/LINK%205.pdf)
- [Revision 1 Bike Frame Bill of Materials (with weblinks)](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/report/bike%20parts%20list.pdf)
- [Revision 2 Bike Frame Bill of Materials (with weblinks)](https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/report/lw%20parts%20list%20web%20links.pdf)

Notes 22/05/2020:
1. Note that this is ready for anyone to take these designs and build a prototype, but more testing needs to be done before it can be certified 100% bombproof. Proceed with caution.
    a. In particular, attention should be paid to the behaviour of the bottom bracket clamp under dynamic loads, and after many load cycles. The best way to test this might be too build one and ride it around for a while.
1. In case it was unclear, the only custom part (apart from cutting tubes to length) is the seat post link. It can be made easily from flat bar with just a hacksaw, a drill, and a file. The part drawing is linked above and should be easy to understand even for people with no engineering knowledge.
1. If the reader wishes to build a prototype, and "cheap" is higher up on their list of priorities than "lightweight," some or all of the aluminium clamps could be used in place of the cast iron clamps.
1. If the prototype is built and there is a problem with rattling, simple rubber washers/gaskets should be used in the swivel sockets. 
    a. This could also help if the surface of the swivel sockets used as "drop outs" (technically, frame ends) does not have a good enough surface finish. Just pop a rubber washer between the frame end and the axle nut.
    b. The number of washers used as spacers depends on the thickness of the washers, especially in the seat post clamp/seatstay assembly. Adjust as appropriate.
1. If there is a problem with the seat post rattling, use a spacer to fill the gap between the seat post and the seat tube. Pvc pipe, shim stock, or folded aluminium foil could be used. To stop it from slipping down the seat tube, drill a horizontal hole through the bottom seatpost below the spacer (through both sides of the tube), and insert a length of threaded bar. Secure it in place with two nuts on the threaded bar inside the seat post, tightened to brace outwards against the ID of the seatpost. Make sure it protrudes far enough to hold the spacer in place, but not to scratch against the ID of the seat tube.
1. A placeholder for the drivetrain was not modelled, because the user can choose to use any number of options - fixed gear, hub gears, cassette gears, or even a belt drive. In the case of fixed gears, chain tensioning would be facilitated by adjusting the sliding clamps. However, regardless of one's preferred drivetrain, it would be advisable to model a simple placeholder and check there is enough clearance, making small adjustments to tube lengths if necessary, before ordering parts.

<img src="https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/clutter/revision%202%20bike.png?raw=true" width="700">
<img src="https://github.com/hannahrosen57/AdjustaBike-2.0/blob/master/CAD/renders/LW%20bike%2010.png?raw=true" width="700"> 
