## Purpose

The goal of this repository is to create a suite of models that can mainly be used for spatial epidemic outbreak simulation. For now, I have made a simple example (`grav_sir.ipynb`) which uses a gravity SIR model to demonstrate the importance
of modeling spatial scale across cities and states. By creating these models as Python classes instead of just using vectorized math, my hope is that they can be extended and modified to incorporate more complex structures such as weighting 
based on mobility data or modeling genetic mutations. Additionally this should allow interactions between units to be somewhat more intuitive to understand. This project is still in the very early stages, but I hope to build it up over the coming months.  
