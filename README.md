# Fluid catalytic cracking unit dataset for evaluation of process monitoring techniques.

## What the repository is about?
This repository provides data from fault-free and faulty operations of a fluid catalytic cracking unit (FCCU). The open source model provided by Santander et al. (https://doi.org/10.1016/j.compchemeng.2022.107900) has been used for simulation; the model's github repository is [here](https://github.com/Baldea-Group/FCC-Fractionator). FCCUs are critical units in oil refineries and are used for cracking VGO into lighters i.e gasoline & LPG. It is a complex process and therefore, a worthy candidate to experiment with the different fault detection and diagnosis (FDD) techniques out there. The picture below shows the five faulty conditions that have been simulated.
![](/Faults_PFD.png)

I'm using this dataset to predict the abnormility before its occurance and validating the same with the help of my domain knowledge.
The model is trained on steady state operation and designed to predict any deviation form steady state. The model anticipates the abnormal behaviour of plant process prameters with some threshold value and also shows the deviated parameters.

## Where is the model?
The model resides at https://github.com/AshuPraja13/FCC-abnormality-detection

## From where referene is used?
https://github.com/Baldea-Group/FCC-Fractionator<br>
https://github.com/ML-PSE/Fluid-Catalytic-Cracking-Unit-Dataset-for-Process-Monitoring-Evaluation
