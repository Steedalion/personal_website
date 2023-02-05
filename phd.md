# Data-based inclusion of humans into cyber-physical manufacturing assembly systems

## Abstract

This work explores the integration of humans into cyber-physical manufacturing systems by constructing a virtual reality simulation to test human behavior. Experiments are conducted to validate the simulation's ability to observe human behavior, and the data collected is used to investigate potential applications. 

Through a number of experiments it was noticed that human trials are expensive and time consuming, inflated by experiment designers tendency to plan for surplus of data. For this reason, a means of automating the experimental design was developed. Using deep learning and informative sampling, an active learning model was developed that substantially reduced the amount of experimental trials needed to model human performance.[^1]

The aforementioned method was extended to Bayesian optimization, which maintains the ability to automated experimental design but also finds the optimum operating conditions, using transparent geometric functions instead of opaque statistical methods. This has the potential to increase industrial adoption due to transparency, but requires more parameter tuning and the design of constraining functions.[^2]

Ethical considerations prohibit AI control of human systems. So the aforementioned method requires a means of measuring the internal human state, such as empathy. Although in its infancy, this work aims to extend the model from steady-state to dynamic and extract the hidden state of the human operator.[^3]  

Candidate: [Clint Alex Steed](README.md)

Supervisor: [Namhun Kim](https://scholar.google.com/citations?user=0dlS09UAAAAJ)



[^1]: Steed, C. A., Kim, N. (2023, **In review since 22-11-22**). Deep active-learning based model-synchronization of digital manufacturing stations using human-in-the-loop simulation. Journal of Manufacturing Systems. [preprint](Docs/SMEJMS-D-22-01279.pdf)
[^2]: Steed, C. A., &#38; Kim, N. (2023, **Accepted**). Automated modeling and control of steady state processes using active learning, [live version](https://github.com/Acadevic/Active-control). <i>IISE Annual Conference and Expo 2023</i>.
[^3]: Steed, C. A., &#38; Kim, N. (2023, **Under review**). Unsupervised hidden state estimation as blind source separation using Auto-encoder RNN filter. <i>15th International Conference on Advanced Computational Intelligence</i> [preprint](Docs/Autoencoder-rnn_filtering.pdf) 