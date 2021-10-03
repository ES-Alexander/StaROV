# Primary Project Aims

1. Find and fix documentation/examples that are incomplete/missing in the Blue Robotics 
website/guides/docs/software, particularly those which are important/essential to 
doing practical design and integration work with our equipment/products
2. Improve and consolidate understanding of the full stack of Blue Robotics products,
including electronics and software

# Desired Qualitative Outcomes

1. Provide a useful reference for a detailed design project on our forums, complete 
with relevant reasoning and calculations
2. Inspire existing and prospective users with an interesting project and a better
understanding of how our components can be integrated together in a custom system
3. Encourage more frequent 'marine robotics' design and development discussion,
beyond product support and announcements

# Design Requirements

## Product Statement

Design a small ROV for sea-floor inspection, capable of being transported in a 35L
backpack, together with all necessary control and communication hardware.

## Physical

- Must fit inside a backpack, with accompanying control and communication hardware
- A fit adult should be able to ride with it on a bicycle
- Total setup (excluding backpack) must be ≤ 15kg, should be ≤ 10kg, and could be ≤ 7kg
- Must be deployable and controllable by a single operator
- Tether must be ≥ 30m, should be 50m, and could be 100m
- Depth rating must be ≥ 10m, should be ≥ 30m, and could be ≥ 50m

## Functionality

- Sonar sea-floor scanning/imaging is required
- 'Terrain-hold' (constant altitude above sea-floor) functionality is required
- Forward-facing and downward-facing cameras are required
- Cameras facing the rear (tether) and above are desired
- Simultaneous multi-camera streaming is required
- Single camera stream recording is required, multi-camera desired
- Real-time object detection capability is desired
- Detected object/obstacles video overlay is desired
- Mapping scanned area is desired, ideally with location-tagged object detections

## Modelling

- All major components must be modelled in mechanical CAD, including at least their
mass, center of mass, and displaced water volume (for 'wet' components)
- Center of mass and center of buoyancy must be simple to recalculate when components
are moved
- All major electronics must be modelled in ECAD, including at least the ports expected
to be useful in an ROV context (e.g. USB required, HDMI not required)
- Linked MCAD and ECAD models is desired
- Wires modelled in MCAD is desired, including with expected colouring
- Modelled components must be in source control, and openly available

## Component Selection

- Blue Robotics components preferred where reasonable, but justification still desired,
including comparison to similar/competing products where relevant
- Components should be selected for low cost at small volumes
- Selected components should be readily available, by purchase or at least source files
(i.e. cannot use unreleased components that would prevent the project from being shared)

## Design Methods + Software

- Open source software and freely available resources are preferred where possible
- Design decisions should be explicitly justified where possible, ideally with a
decision tree displaying attempted branches alongside alternatives that have been
dismissed or not yet explored
- Calculations should be documented and explained

## Cost

- Final product components (excluding tether, lights, and scanning sonar) must be less
than the BlueROV2, should be less than 90%, could be less than 80%
- Software used should be readily available for free/at a low cost to at least hobbyists
and research institutes/organisations, preferably everyone
- Manufacturing costs outside those for purchased components should be minimised

## Timeline

- ROV must meet requirements and be usable within 2 years, should be within 1 year,
could be within 6 months
- Project as a whole has no required completion date (could be an ongoing development)
- Progress summaries must be reported monthly in the Blue Robotics forum 'build'
category, could be reported fortnightly
- Dive logs should be posted at least every two months once relevant, preferably every
month
