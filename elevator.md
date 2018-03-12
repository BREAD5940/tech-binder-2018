# Elevator

#### Design Goals & Criteria:

* Can reach both the Scale and Switch
* Quickly and accurately can raise to an inputted height
* Tall enough to place a Power Cube on the top of another that has already been scored
* Fits within the sizing constraints at the beginning of the match

#### Prototyping

* We had already decided that an elevator was the easiest lifting device to package and simplistic to build (as we had never done so)
* Two general concepts emerged
    * The "Adrian Elevator" - inspired by 1678 in 2016
    * The "Cheesy Elevator" - inspired by 254 in 2011

* Adrian Elevator (Cascade Lift):
    * Pros -
        * Uses loops of chain to raise and lower
        * No cables to deal with
        * Method of actuation is comparatively stronger
    * Cons -
        * More complex
        * Contains more failure modes
        * Less experience in the FIRST community to learn from

* Cheesy Elevator (Continuous Lift):
    * Pros -
        * Less complex actuation system
    * Cons -
        * Cable spool and assorted devices would have to be designed
        * Takes up more space on robot interior

We decided on a hybrid of the two designs, using a tube and bearing block solution found on 254's various lifting robots in 2011, 2008, and 2007, but with a highly similar cascading actuation system to 1678's robot in 2016.

#### Elevator Overview

* Custom bearing rollers end caps and blocks
    * Allows smooth, reliable, and frictionless motion
    * Grants accurate programmatic control of elevator
    * Holds elevator frame together in critical areas
* Cascading chain lift system
    * Powered by a single 775pro attached to a VexPro VersaPlanatary with x:x reduction
    * Two loops of chain move the inner frame and carriage
    * Contains PID loop and CTRE Mag Encoder for consistent control and positioning
    * Can reach ~8 feet, above a level of cubes already stacked on Scale