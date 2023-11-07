# Instructions for the Virtual Catapult Design of Experiments (DOE) Project

## Objective:
The aim of this project is to apply the principles of Design of Experiments (DOE) to optimize the performance of a virtual catapult, which is available at https://sigmazone.com/catapult/. The objective is to find the optimal catapult settings to reach a specific target distance.

## Project Steps:

1- Understanding the Problem: The first step in the project is to comprehend how the catapult functions and which variables can be controlled. We use the catapult simulator to become familiar with the control variables and observe how they affect the distance the catapult can propel.

2- Experiment Design: Once we have a good grasp of the problem, the next step is to design the experiment. To do this, we need to determine how many levels you want for each factor, how many repetitions we will conduct, and the sequence in which we will perform the experiments. We can start with a complete factorial design, followed by a fractional factorial design if necessary.

3- Experiment Execution: After designing the experiment, we carry out the experiment by adjusting the variables according to the design and recording the achieved distance for each configuration.

4- Data Analysis: Following data collection, we analyze it. We employ the pyDOE2 library to perform analysis of variance (ANOVA) and other necessary analyses to identify the most significant factors.

5- Optimization: Based on the analysis, we use optimization techniques to find the best catapult configuration to achieve the desired distance.
