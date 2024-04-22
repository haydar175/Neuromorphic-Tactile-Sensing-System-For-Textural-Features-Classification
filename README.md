# Neuromorphic-Tactile-Sensing-System-For-Textural-Features-Classification
This repository contains the implemented scripts corresponding to the research presented in the manuscript "Neuromorphic Tactile Sensing System For Textural Features Classification." You can access the manuscript in the IEEE Sensors Journal via the following DOI: https://doi.org/10.1109/JSEN.2024.3382369.

First, we discuss the encoding procedure where we convert the raw tactile signals of artificial gratings into spikes by modeling SA-I and RA-I mechanoreceptors. Then, we tune the refractory period of the encoding models using the Leaky-Integrate-and-Fire neuron implemented in the Brian2 Simulator.

In the second part of this tutorial, we explain the implementation procedure of the recurrent spiking neural network (RSNN). Following this, we will train and test the RSNN through the surrogate gradient descent on the encoded dataset. The datasets are encoded with different combinations of refractory period for the RA-I and SA-I mechanoreceptors.  

![Picture1](https://github.com/haydar175/Neuromorphic-Tactile-Sensing-System-For-Textural-Features-Classification/assets/69388118/812bd4b7-91ba-4278-ada7-54759d4943ba)
