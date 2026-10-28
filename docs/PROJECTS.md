# Engineering project notes

These notes complement the existing portfolio pages; they do not replace any website files, pictures or descriptions. Each entry links to the corresponding HTML page and the existing image folder. Technical statements below are limited to information shown in those pages. Where a value comes from the original page rather than a reproduced calculation, it is described accordingly.

## 1. Antenna torque-balancing system
**[Existing detail page](../project1.html)** · Images: [Antenna](../assets/img/Antenna/)

**Challenge.** Develop a counterbalancing concept for an antenna-tracking assembly so its weight and torque can be accommodated more smoothly.

**My work.** As part of the University of Toronto Aerospace design team, researched torque-balancing approaches and proposed a sheet-metal attachment carrying approximately 3 kg of counterweight. Modeled the design and considered force and displacement in simulation.

**Evidence currently shown.** Prototype render, metal-plate drawings and displacement plots. The original page reports a simulation with a 50 N applied load and a maximum displacement of 0.097 mm; the underlying model inputs and verification are not included in this repository.

**To add later.** Free-body diagram, torque balance and counterweight location calculations, mounting details, material/mesh assumptions and test results.

## 2. Hobbyist FDM 3D printer
**[Existing detail page](../project2.html)** · Images: [3D Printer](../assets/img/MIE243/3dprinter/)

**Challenge.** Conceptualize an entry-level fused-deposition-modeling printer that balances accuracy, speed and cost for a MIE243 design project.

**My work.** Designed or contributed to the lead screw, printing-bed x/y motion mechanism, z-axis support, hot-end concept and extrusion/nozzle mechanism; used CAD mechanical mates to illustrate motion.

**Evidence currently shown.** CAD assembly renderings and component images. The website does not provide a verified print-quality, speed or price benchmark.

**To add later.** Travel range, positioning resolution, lead-screw sizing, motion-transmission selection, bill of materials and print-test measurements.

## 3. Gearbox design
**[Existing detail page](../project3.html)** · Images: [Gearbox Assembly](../assets/img/MIE243/Gearbox%20Assembly/)

**Challenge.** Design a feasible gearbox assembly with appropriate gear, shaft and housing arrangements.

**My work.** Modeled gears and input/output shafts, considered gear ratios and component selection, and worked with SolidWorks and Dremel 3D printing to bring an assembly concept into physical form.

**Evidence currently shown.** Assembly photographs and CAD drawings. The original page does not document the final ratio, load specification or test procedure.

**To add later.** Target speed/torque, tooth counts, ratio calculations, shaft sizing, bearing selection and dimensional drawings.

## 4. Can-opener mechanism redesign
**[Existing detail page](../project4.html)** · Images: [Can opener](../assets/img/MIE243/Can%20opener/)

**Challenge.** Study an existing manual can-opener mechanism and redesign its transmission to increase output torque.

**My work.** Created the original and modified mechanism models, redesigned the larger and smaller gears, and used SolidWorks mates to check the assembly's intended motion.

**Evidence currently shown.** Comparison drawings and CAD views. The original page reports a **50% increase in output torque** for the modified design; supporting gear ratio and efficiency calculations are not yet published here.

**To add later.** Gear-tooth counts, torque ratio derivation, friction assumptions and comparison of turning effort.

## 5. Screwdriver mode-switching mechanism
**[Existing detail page](../project5.html)** · Images: [Screwdriver](../assets/img/MIE243/Screwdriver/)

**Challenge.** Recreate or model a screwdriver mechanism able to switch between electronic and manual operation.

**My work.** Explored a planetary gear/carrier assembly and button-operated flat-spring locking concept. The intended mechanism locks the hex shank for manual control and releases it to return to the default electronic mode.

**Evidence currently shown.** Mechanical model images; the project page describes the concept but does not include prototype durability or force test results.

**To add later.** A labeled actuation sequence, spring force calculation, exploded assembly, wear considerations and physical test observations.

## 6. Jigsaw mechanism design
**[Existing detail page](../project6.html)** · Images: [Jigsaw](../assets/img/MIE243/Jigsaw/)

**Challenge.** Represent and document a jigsaw mechanical assembly.

**My work / available evidence.** The page contains assembly drawings and CAD screenshots. Its skills bullets appear to describe a screwdriver and should not be treated as confirmed jigsaw-specific work.

**To add later.** A verified design brief, crank/slider or other specific motion-conversion architecture, stroke calculation, individual contribution and testing. No unverified mechanism specifications are asserted here.

## 7. V6 engine SolidWorks assembly
**[Existing detail page](../project7.html)** · Images: [V6 Engine](../assets/img/V6%20Engine/)

**Challenge.** Build a V6 engine CAD assembly to understand component relationships and mechanical motion.

**My work.** Modeled engine parts in SolidWorks, assembled components and explored their motion. The original page references cylinder blocks, rocker arms, pistons, cylinder heads and exhaust manifolds, as well as the four-stroke engine cycle.

**Evidence currently shown.** CAD screenshots. This is a modeling and motion-analysis project, not a claim of a built or running engine.

**To add later.** Crankshaft/piston linkage constraints, component dimensions, animation, interference checks and a short account of assembly challenges.

## 8. Brighter Pages community outreach
**[Existing detail page](../project8.html)** · Images: [Brighter Pages](../assets/img/Brighter%20Pages/) and [Brighter Pags](../assets/img/Brighter%20Pags/)

**Challenge.** Improve educational access through resource collection and outreach.

**My work.** Helped coordinate a project supplying over 500 books and school materials to a school in central Vietnam, organized an education-focused seminar with over 200 attendees, and managed social media content.

**Evidence currently shown.** Event and community photos. This is a leadership/community entry rather than an engineering design project.

**To add later.** Role breakdown, logistics timeline, feedback and outcomes.

## 9. Mancor Industries manufacturing improvement
**[Existing detail page](../project9.html)** · Images: [Mancor](../assets/img/Mancor/)

**Challenge.** Maintain trunnion welding production while reclaiming floor space and improving process flow.

**My work.** Reworked the manufacturing-cell layout, developed tooling/fixture concepts, performed time studies and documented standardized work for welding, robotic welding and shot-blast operations. The original website describes moving toward one-piece flow. The internship also covered manufacturing exposure across laser cutting, bending, welding, machining and painting.

**Results from project records.** The redesigned cell required approximately **30% less floor space**, and its cycle time changed from **2 h 30 min to 1 h 55 min** (about a **23%** reduction based on those rounded times). These values are provided as project results; detailed time-study sheets are not published here.

**Evidence currently shown.** Photographs and work examples. Sensitive workplace documentation should not be uploaded without permission.

**To add later.** An anonymized before/after layout, non-confidential process map, time-study method and engineering tradeoffs.

---

## How to strengthen an individual project README

When source files can be shared, a dedicated repository can follow this structure:

```text
project-name/
├── README.md                # Problem, role, approach, result
├── images/                  # Original photos with captions
├── cad/                     # STEP, PDF drawings or permitted source files
├── calculations/            # Engineering assumptions and calculations
├── firmware/                # Code, if applicable
└── tests/                   # Test plan and recorded measurements
```

Use the following questions for each write-up:

1. **Problem and constraints:** What had to work, under what loads, sizes, costs or time constraints?
2. **My contribution:** What did I personally design, analyze, build, coordinate or test?
3. **Engineering decisions:** What concepts did I compare, and why was one chosen?
4. **Verification:** What measurements, analysis or test results support the outcome?
5. **What I'd improve:** What limitations remain and what would I test next?

### Documentation boundary

This folder does not include proprietary CAD, confidential internship materials or unverified performance claims. The original portfolio pictures and HTML files are intentionally untouched.
