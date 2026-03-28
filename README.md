# Echo State Networks for Epidemic Dynamics

This project explores how epidemic dynamics can be learned directly from data using **Echo State Networks (ESNs)**, a form of reservoir computing.

Based on the paper:
*“Reservoir Computing on Epidemic Spreading: A Case Study on COVID-19 Cases”*

I implemented an ESN from scratch and built pipelines for both **synthetic epidemic data (SIR/SIRS, including multi-wave scenarios)** and **real COVID-19 data**, focusing on understanding how temporal patterns can be captured without explicitly modeling system parameters.

What I found particularly interesting was how even stochastic and noisy processes can exhibit structured, learnable behavior when viewed at the right scale.

Repository details:
ESN.ipynb : has the actual implementation code

Indonesia_pred, Norway_pred, Zimbabwe_pred : output images from ESN forecasting (you can get it by running the code too)
