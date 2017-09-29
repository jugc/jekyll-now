---
layout: page
title: Work
permalink: /work/
---
# Projects

The projects detailed in this section, intend to illustrate the main methods, tools and results obtained during my academic career. Some of the results were published in peer-reviewed journals, and others are code that was developed during my Ph.D. and subsequent years. Due to NDAs, it is not possible to share all the code, unfortunately.

## Data Analysis Module for Hybrid Energy Harvesting

This is a python module I implemented for my recent postdoc project at the Institute of Material Science at EPFL (École polytechnique fédérale de Lausanne).

The project I worked on during my time at EPFL, involved a lot of hardware testing for a hybrid energy harvesting device, with multiple experiments under different conditions. These experiments generated a lot of data that:

1. Had a random number of repetitions, and
2. Within each repetition, there was a random number of tests.

This generated a dynamic dataset that changed with every experiment. Therefore, this module was written in order to:

1. Accommodate to the changing datasets (number of repetitions, tests, variables) in an automatic way,
2. Transform the raw data into a pandas dataframe for easy analysis,
3. Basic time and frequency-domain analysis (FFT and PSD), and

The implementation follows an object-oriented approach with a class definition that is congruent with the data associated to the experiments.

The module is hosted [here](https://github.com/jugc/eh_module), however, the data from the experiments cannot be shared due to confidentiality agreements with the company involved in the project.

# Publications

1. **Gallego-Calderon, J.**, Natarajan A and Cutululis, N. (2016) *[“Ultimate design load analysis of gearbox bearings under extreme loading.”](http://onlinelibrary.wiley.com/wol1/doi/10.1002/we.2008/full)* Wind Energy, 1099-1824.
2. **Gallego-Calderon, J.**, and Natarajan A. (2015) *[“Assessment of Wind Turbine Drive-train Fatigue Loads Under Torsional Excitation.”](http://www.sciencedirect.com/science/article/pii/S0141029615005714)* Engineering Structures, 103, 189–202.
3. **J. Gallego-Calderon**, A. Natarajan and N. Dimitrov (2015). *[“Effects of bearing configuration in wind turbine gearbox reliability.”](http://www.sciencedirect.com/science/article/pii/S187661021502175X)* Energy Procedia, 80: 392–400.
4. **J. Gallego-Calderon**, K. Branner, A. Natarajan, N. Cutululis and J. Hansen. *[“Electromechanical Drivetrain Simulation.”](http://orbit.dtu.dk/fedora/objects/orbit:123931/datastreams/file_7a93ab44-e1b4-4a04-b9fa-b349801a6183/content)* 9th PhD Seminar on Wind Energy in Europe, Gotland, Sweeden, 2013.
5. **Gallego-Calderon, J**. and Bengiamin, N. (2013) *[“Efficient Drives for Single-phase AC Motors: Analysis and Applications.”](http://www.ijme.us/issues/spring2013/abstracts/Z__IJME%20spring%202013%20v13%20n2%20(paper%203).pdf)* International Journal of Modern Engineering, 13(2):25–33.
