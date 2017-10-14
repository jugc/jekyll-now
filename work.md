---
layout: page
title: Work
permalink: /work/
---
# Projects

The projects detailed in this section, intend to illustrate the main methods, tools and results obtained during my academic career. Some of the results were published in peer-reviewed journals, and others are code that was developed during my Ph.D. and subsequent years. Due to NDAs, it is not possible to share all the code, unfortunately.

## Data Analysis Module for Hybrid Energy Harvesting

This is a python module I implemented for my recent postdoc project at the Institute of Material Science at EPFL (École polytechnique fédérale de Lausanne).

The project I worked on during my time at EPFL, involved hardware testing of a hybrid energy harvesting device, with multiple experiments under different operational conditions. These experiments generated a large amount of data that:

1. Had a random number of repetitions, and
2. Within each repetition, there was a random number of tests.

This generated a dynamic dataset that changed with every experiment. Therefore, this module was written in order to:

1. Accommodate to the changing datasets (number of repetitions, tests, variables) in an automatic way,
2. Transform the raw data into a pandas dataframe for easy analysis,
3. Basic time and frequency-domain analysis (FFT and PSD), and

The implementation follows an object-oriented approach with a class definition that is congruent with the data associated to the experiments.

The module is hosted [here](https://github.com/jugc/eh_module), however, the data from the experiments cannot be shared due to confidentiality agreements with the company involved in the project.
