# Intake

#### Design Goals & Criteria:

* Quickly and efficiently intake Power Cubes
* Place cubes accurately and reliably on the scale & switch
* Needs to be reliable and serviceable

#### Prototyping

* We knew we wanted to go with an active roller system
    * "Touch it, own it"
* Needed to package into elevator carriage
* Strong and bend resistant
    * Being held outside bumpers

Two general prototypes were considered and manufactured:

* Prototype 1: "Pincher"
    * Pros -
        * Relatively simplistic
        * Less moving parts
        * Increased servicablity
    * Cons -
        * Compliant arms were difficult due to geometry of intake
        * Significant amount of the intake has to "stick out" through the elevator frame into the robot

* Prototype 2: "Sideswipe"
    * Name and inspiration from Team 1114's 2015 robot
    * Pros -
        * More flexible in different orientations
        * Could pick up in more orientations than "pincher" could
        * Packages compactly for elevator usage
    * Cons -
        * Due to smaller size more mechanisms are stacked inside
        * Heavier due to the nature of the design

Considering the various characteristics of each device, we decided to go with a modified "Sideswipe" variant.

#### Intake Overview

* Dual intake arms
    * Actuates with pneumatic cylinders
    * Can either spin to outtake cube or simply open arms and drop cube on plate
    * Each contains two AndyMark 4" Compliant Wheels (35A)
    * Can center and align cube for intaking
* 1/4" Plate CNC route major plates
    * Houses two VexPro VersaPlanatary gearboxes at x:x using one 775pro each
    * Conveys power to intake wheels and arms using GT2 belting from WestCoast Products
    * Attaches to pivoting carriage
    * Contains two IR distance sensors for cube detection and automatic centering