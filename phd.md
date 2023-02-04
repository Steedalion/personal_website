# Data-based inclusion of humans into cyber-physical manufacturing assembly systems

## Abstract

This work investigates including humans into cyber-physical manufacturing systems by attempting to build a vertical slice. This study includes building a virtual reality simulation is developed as a test bed, conducting experiments are to verify the simulations ability to observe human behavior, and investigating applications of the data acquired. 

Through a number of experiments it was noticed that human trials are expensive and time consuming, inflated by experiment designers tendency to plan for surplus of data. For this reason, a means of automating the experimental design was developed. Using deep learning and informative sampling an active learning model was developed that substantially reduced the amount of experimental trials needed to model the human performance.[^1]

The aforementioned method was extended to the more general Bayesian optimization form, which retains automated experimental design ability (exploration), but extension also allows finding the optimum operating conditions (exploitation). The method developed here is distinct from previous methods as it relies on transparent geometric functions, where previous methods rely on opaque statistical methods. This has the potential to increase industrial adoption due to transparency.[^2]

Ethical considerations prohibit the use of AI to control human systems. For this reason the aforementioned method requires a method of measuring the internal human state (empathy). Modeling human states such as learning and fatigue tend to be dynamic, were the industrial systems in question are assumed to be steady-state. Although in its infancy, this work attempts to (1) extend the model from steady-state to dynamic and (2) extract the hidden state of the human operator.[^3]  

Candidate: Clint Alex Steed

Supervisor: Namhun Kim



[^1]: Steed, C. A., Kim, N. (2023, **In review since 22-11-22**). Deep active-learning based model-synchronization of digital manufacturing stations using human-in-the-loop simulation. Journal of Manufacturing Systems. [preprint](Docs/SMEJMS-D-22-01279.pdf)
[^2]: Steed, C. A., &#38; Kim, N. (2023, **Accepted**). Automated modeling and control of steady state processes using active learning, [live version](https://github.com/Acadevic/Active-control). <i>IISE Annual Conference and Expo 2023</i>.
[^3]: Steed, C. A., &#38; Kim, N. (2023, **Under review**). Unsupervised hidden state estimation as blind source separation using Auto-encoder RNN filter. <i>15th International Conference on Advanced Computational Intelligence</i> [preprint](Docs/Autoencoder-rnn_filtering.pdf) 