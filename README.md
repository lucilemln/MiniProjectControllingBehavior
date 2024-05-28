# Jump/Escape via Descending Control in Response to Visual Looming
This project focuses on understanding the escape jump mechanisms in flies using the NeuroMechFly model. Detailed simulations aim to uncover the intricate relationship between biomechanics and neural processes involved in this behavior, with implications for neurobiology and bio-inspired robotics.

## Files and Functionality
1. jumptestV0.py
This script codes the jump mechanism using the old API. It serves as the baseline for the escape jump behavior in flies.

2. jumptestV1.py
This script attempts to replicate the functionality of jumptestV0.py but using the new API. It is an updated version aimed at improving the accuracy and efficiency of the simulation.

3. visual_test.py
This script performs the detection of an object. When an object is detected, the fly turns in response. It focuses on simulating the visual perception aspect of the escape behavior.

4. jump_to_visual_looming.py
This script integrates the jump mechanism with the visual looming detection. It attempts to trigger the escape jump when an object is detected, simulating the natural response of a fly to a looming threat.

## Requirements
To run the simulations and scripts, ensure you have the following installed:

Python
Jupyter Notebook
FlyGym
FlyGym V1


## Installation

Clone the following repository: https://github.com/lucilemln/MiniProjectControllingBehavior.git

## Future Work
Integrate additional factors such as angle size and object speed to improve the accuracy of visual looming simulations.
Enhance the preparatory phase of the jump and the overall quality of the jump to better capture the complexity of the escape maneuver.
