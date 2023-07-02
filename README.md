# Malhas-et-al.-in-prep
This GitHub project focuses on the study of low mass galactic outflows for my upcoming paper where we focus on 5 low-Z dwarf galaxies observed with the Cosmic Origins Spectrograph (COS). 
The aim is to understand the properties and dynamics of outflows in galaxies with lower stellar masses. While the paper is primarily concerned with a few FUV absorption profiles, the hope is that the code will eventually be 
universal in its ability to calculate the desired outflow characteristcs (velocity and equivilent width). Future iterations of the program will aim to make it easy for one to plug in their own Flux, Cont, Error, and Wavelength
arrays from their observations, and from there be able to perform the same calculations. As it stands, I have much work to do in order to correct a few of the less user-friendly aspects of the code. Feel free to reach out with
any questions if you would like help running the code on your own galaxy data and I'd be happy to assist. Some of the trickier parts are as follows: Spline fitting (requires lots of visual input), Constraining the 
min and max velocity ranges (so as to not include unreasonable values during the Monte Carlo Operations) ,Saving the data and not needing to rerun the time consuming MCMC calculations , and galaxies with only one or two
transitions that were not observed being plotted later on (this should be an easy fix by migrating to the pandas df format rather than numpy arrays for everything but I wrote the code rather early in my 
python endeavor). Everything else
should work rather well so long as you rename your variables for whatever galaxy you are doing. 

Introduction
Galactic outflows are phenomena where gas is expelled from galaxies into the intergalactic medium. They play a crucial role in the overall evolution of galaxies, affecting their star formation rates, chemical enrichment, and gas content. While extensive research has been conducted on outflows in massive galaxies, the investigation of low mass galactic outflows remains relatively understudied. This project aims to bridge this gap and shed light on the unique characteristics and implications of outflows in low mass galaxies.

Contents
This repository contains the following components:

Figure 1-10: This directory includes the raw image files as well as the code for generating the plots in the order they are featured in the paper.
Paper_Plotter.ipynb: Here you can find the google collab notebook where all the calculations and figures can be found.
Results: This section presents the results of the study, including plots, figures, and tables illustrating the relationships between outflow properties and host galaxy characteristics.
References: A list of references and relevant literature used in this project.
Usage
To utilize this repository, follow these steps:

Clone the repository to your local machine using the following command:

bash
Copy code
git clone https://github.com/Astro-CMalhas/Malhas-et-al.-in-prep
Access the relevant directories to explore the data, code, documentation, and results.

Follow the instructions provided in the documentation to understand the analysis techniques and reproduce the results.

Contribution
Contributions to this project are welcome. If you have any ideas, improvements, or findings related to dwarf galaxies, feel free to submit a pull request. Please ensure that your contributions align with the goals and scope of this project.

Contact
If you have any questions or suggestions regarding this project, please contact Project Lead.

We appreciate your interest and contribution to the study of low mass galactic outflows.

Happy exploring!
