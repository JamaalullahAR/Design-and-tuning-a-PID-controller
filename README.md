# Design and tuning a PID controller

## Overview
This project required the implementation of a PID controller for a UAV drone. The drone needed to achive certain targets which was required from the assignment. The full report can be seen in the report PDF in the added files.

## Objectives
- Calculate the correct transfer functions required.
- Add the PID controller to the given SIMULINK model.
- Ensure the drone output achieves the target.
  
## Tools and concepts used
- Control system theory (understanding PID controller and how each component affects the output)
- SIMULINK
- LyX and LaTeX for writing up the report

## Methodology
- Calculated the transfer functions for pitch rate loop, pitch angle loop from the block diagrams.
- Used root locus plot to understand gains which would keep the pitch angle loop stable.
- Building a controller using the initial calculated TF.
- The total PID controller would have a step reference input from 0m to 2m at 2 seconds. The controller had to achieve a step response of 2% settling time below 3 seconds, and a zero steady-stete error.

## Results
- The transfer functions calculated for pitch rate loop and pitch angle loop were correct.
- The calculated disturbance transfer function was unfortunately calculated incorrectly.
- However, the final output of the drone managed to reach the desired step response 2% settling time of approximately 2.2 seconds and a zero steady state error.
- From the animation, the drone works as well as I could have made it, from whatever I had learnt in my course.

## Project images


## What I learnt
- The most important thing I learnt was how the PID gains affected the plant output.
- Managed to gain a better understanding of SIMULINK and how to use it.
- How to identify and calculate transfer functions from block diagrams.


