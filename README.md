# Constraining pulsar ellipticites through hierarchical Bayesian inference

Performs inference on posterior gravitational wave signal strength (h0) samples redrawn as ellipticities.


## Directory:

### [hier_numpyro:](Notebooks/hier_numpyro.ipynb)
Holds all models, runs them locally, some basic plotting.

### [extract_posterior_samples:](Notebooks/extract_posterior_samples.ipynb)
Extracts posterior samples from h5py, resamples using jacobian and creates csv. Models run on this.

### [hyperparameter_tests:](Notebooks/hyperparameter_tests.ipynb)
Plots hyperparameters posterior distributions against prior for various models. Relies on csv created in hier_numpyro

### [simulated_data:](Notebooks/simulated_data.ipynb)
Simulates hanford and livingston detection data from a pulsar-sourced gravitational wave.