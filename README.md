# Overview
Modified version of University of Minnesota Prof. Marc Riedel's stochastic simulation software. Homework files from EE 5393 are also in this repo.

### What I changed
- Added optional CLI arg max_events:
  - aleae_main.cc:23
  - aleae_main.cc:82
- Added event-limit parameter to simulation config:
  - aleae.h:107
- Enforced stop condition at max_events reaction firings:
  - aleae_stoch.cc:35
- Added variance output per species (var [..]) using E[X^2]-E[X]^2:
  - aleae_main.cc:89
  - aleae_main.cc:174
- Updated usage docs:
  - README.txt:3
