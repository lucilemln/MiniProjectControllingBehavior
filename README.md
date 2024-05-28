# Jump/Escape via Descending Control in Response to Visual Looming
## Introduction
This project focuses on understanding the escape jump mechanisms in flies using the NeuroMechFly model. Detailed simulations aim to uncover the intricate relationship between biomechanics and neural processes involved in this behavior, with implications for neurobiology and bio-inspired robotics.

## Table of Contents
* [Getting Started](#getting-started)
* [Usage](#usage)
* [Files and Functionality](#files-and-functionality)
* [Futur Work](#futur-work)
## Getting Started

### Prerequisites

To run the simulations and scripts, please ensure the following are installed:

- *Python*, *Jupyter Notebook*, *matplotlib*, *numpy*, *tqdm*, *gymnasium*, *flygym*, *flygym v1*, *dm_control*, *IPython*
  
## Usage 
- Clone the Repository: Clone this repository to your local machine using the following command: https://github.com/lucilemln/MiniProjectControllingBehavior.git

## Files and Functionality
- **jumptestV0.py**
This script codes the jump mechanism using the old API. It serves as the baseline for the escape jump behavior in flies.

- **jumptestV1.py**
- This script attempts to replicate the functionality of jumptestV0.py but using the new API. It is an updated version aimed at improving the accuracy and efficiency of the simulation.

- **visual_test.py**
This script performs the detection of an object. When an object is detected, the fly turns in response. It focuses on simulating the visual perception aspect of the escape behavior.

- **jump_to_visual_looming.py**
This script integrates the jump mechanism with the visual looming detection. It attempts to trigger the escape jump when an object is detected, simulating the natural response of a fly to a looming threat.


## Future Work
Integrate additional factors such as angle size and object speed to improve the accuracy of visual looming simulations.
Enhance the preparatory phase of the jump and the overall quality of the jump to better capture the complexity of the escape maneuver.
