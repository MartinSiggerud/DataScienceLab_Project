# DataScienceLab_Project
Project in Data Science Lab at Politecnico di Torino 

Within the field of particle physics, a long-standing task of interest is detecting the positions where particles (e.g., electrons) pass in their trajectories. Some sensors are capable of detecting the passage of these particles and, following that, the position of the particles themselves. One such sensor is the RSD (Resistive Silicon Detector). This sensor has a 2-dimensional surface within which it can detect the passage of particles.

When a particle passes through the sensor (green area in Figure 1), various metallic pads are used to measure a signal. In the specific sensor of interest, the pads have a “snowflake” (or star, or asterisk) shape. In particular, in Figure 1 there are 12 pads within the sensor.
The passage of a particle through the sensor is referred to as an event. For each event, each pads measures a signal: the properties of this signal (the inputs to the problem) are correlated with the position of the passing particle. Since the surface is 2-dimensional, the position of the particle (your target) is defined as a pair of (x,y) coordinates.
The goal of this project is to build a data science pipeline that predicts for each event, given as inputs the characteristics of the signals measured by each pad, the target (x,y) coordinates where the particle of interest passed.

NOTE: You have to download the raw .csv files from here: https://drive.google.com/file/d/1RqoGwJ7lkcXc7INE9hINUQZW2O8ltBcB/view?usp=drive_link 
