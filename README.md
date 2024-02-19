# CUDA-spectral

## Inspiration
For a researcher requires to set up a solver to verifies some ideas based on spectral method, one has many options to choose, outstanding python libs like Dedalus, shenfun. But so far I could not find the developers have intention
to accelerate their programme with CUDA libs. So this repository I want to construct a python lib of common-used spectral method accelerated by CUDA, for the convenience, we still choose python as
primary language, where we hand over the computational module to CUDA and provide corresponding python interface.
