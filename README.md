# orca-noise-model
A model for predicting bioacoustic impacts of noise on soniferous organisms, built initially for orcas calling or echolocating in vessel noise.

This model was built through a collaboration of [Oceans Initiative](https://github.com/oceans-initiative/) and Beam Reach with funding support from the National Fish and Wildlife Federation (NFWF). The goal of our project was to retrospectively model the noise levels that SRKWs experienced back in 2003-5 when Oceans Initiative studied their behavior from land using theodolites to track the movements of focal whales and the distribution of nearby boats. More recent behavioral data collected by Oceans Initiative in 2020 was combined with theodolite and AIS data to model "modern" vessel noise conditions for comparison with the modeled historic conditions.

As of 2022, [the model](https://github.com/oceans-initiative/beam-reach-track-analyzer/blob/master/python-code/Analysis_RLs.py) uses only simple logarthmic algorithms for computing transmission loss. Future features could include frequency-dependent absorption, and then incorporation of more complex propagation models (e.g. [parabolic equation, normal mode, wavenumber integration, and ray models](https://www.nap.edu/read/10564/chapter/6#110), possibly leveraging open source code available from [oalib-acoustics.org](https://oalib-acoustics.org/)(initiated by Mike Porter; now managed by U.S. Navy's Office of Naval Research). It is written in Python, though this repository also includes some R scripts used for statistical analysis and visualization of the noise model outputs.

# Development team

* Lead: Val Veirs, Beam Reach
* Beta-testing and documentation: Scott Veirs, Beam Reach



