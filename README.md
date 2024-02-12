# Final_year_Project
Using deep learning to boost dark matter searches at the LHC in top-anti-top quark events. Very experimental code, not particularly readable or optimized

Boosting Dark matter searches at the LHC using machine learning.


The Large Hadron Collider (LHC) at CERN is the world’s most powerful particle accelerator. Following
an upgrade it resumed colliding protons at a centre of mass energy of 13.6 TeV in 2022. This offers a
great opportunity to develop new techniques for searches for new physics beyond the Standard Model (SM) of
particle physics. We believe the SM is incomplete because of, e.g., the fine-tuning of the Higgs boson mass
and the lack of a viable dark matter candidate. Supersymmetry and other theories that solve these problems
predict production of new particles at the LHC. However, detecting a signal of the new particles will be very
challenging because it will be buried under a large background of known SM processes. Furthermore,
the new particles might not interact with detector material and only appear as ”missing energy”. The aim
of this project is to develop new techniques for distinguishing a potential new physics signal from the SM
background. This repo investigates how machine learning can take advantage of subtle differences between
a new physics signal and SM background and improve the sensitivity of the new physics searches.

The code in this repository focusses on the top-anti-top Higgs production mode and its assoociated background. 
The data used on this code was 13 TeV simultaed datg and is normalised to 300 fb^-1 to simukate run 3 at the
LHC. 

All code was carried out on the Bristol Dice cluster and will not be able to run without if it is not on
this server as all data is stored here.


## Table of Contents
* Initial_Testing
    - The code used for initial tests and exploratory data analysis at the start of the project.
* Data_Manipulation
  - Covers preprocessing and cleaning of the data, which was needed to input it into different types of NN.
* FNN (MLP)
  - Provides code for all general types of Feedforward Neural Networks in this project.
* RNN
    - Provides code for all general types of Recurrent Neural Networks in this project.
* Combined (FNN+RNN)
    -  Provides code for all general combined models, which are a concatenation of the FNN and RNN.
* Multiclass Classifier
     - Provides code for all general types of Recurrent Neural Networks in this project.
* Evaluation_Plots
    - Demonstrates the code used to create the plots used in my final report.

