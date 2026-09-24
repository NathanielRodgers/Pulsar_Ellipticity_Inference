# Constraining pulsar ellipticites through hierarchical Bayesian inference

Performs inference on posterior gravitational wave signal strength (h0) samples redrawn as ellipticities.


## Directory:

### hier_numpyro:
Holds all models, runs them locally, some basic plotting

### extract_posterior_samples:  
Extracts posterior samples from h5py, resamples using jacobian and creates csv

### hyperparameter_tests:
Plots hyperparameters posterior distributions against prior for various models. Relies on csv created in hier_numpyro

### simulated_data: 
Simulates hanford and livingston detection data from a pulsar-sourced gravitational wave.