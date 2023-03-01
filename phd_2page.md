# Data-based inclusion of humans into cyber-physical manufacturing assembly systems

Manufacturing assembly is a major indicator in a countries economic growth. Humans remain a crucial resource in assembly due to their flexibility. Human inclusion in smart manufacturing, cyber physical production systems, and assembly has recieved a sharp increase in interest deu to economic and social changes.

Human fatigue is an important consideration as it affecrs both production outputs and human health. In fact, we can not measure fatigue directly, only the effects thereof. It affects a systems throughput rate [], qaulity output, where high level increase risk of injury and long term health issues. Two methods of data-acquisiton are human-siganls and production signals. Human signal have seen commercial success in static tasks like pilots and long distance drivers [] but are impractical in flexible environment like manufacuturing assembly. 

## Chapter 1
The insight is that by using VR we can postpone many of the data acquiisiton challenges. The issue then becomes confirming that VR simulations are suitable for measuring these prodution signals. This study simulates a series of tasks and confirms that VR can observed fatigue related phenomena.

### Results
The VR simulation results show that we can observe the throutput rate predicted by Wright-learning [] and quality risk index [].

### Results
We conclude that VR can be used to simulate assembly processes to gather throughput rate and assembly quality data. 

### Implications 
The data obtained can be used to construct human performance models. This allows comparing the performance of human workstations and workschedule performance.

## Chapter 2
Human trials are time consuming, costly, and labor intensive. This work investigates experimental design as it has the potential to reduce the amount of trials conducted by suggesting informative samples. Few previous works consider VR human experiment systems using linear models and conducting offline experimental design. The proposed solution uses an online deep learning model.

### Results
When compared to random sampling this method significantly reduced the number of trials.

### Implications
This solution uses online experimental design, resulting in automated VR experiments. When combined with the previous works this enables remote, concurrent, and automated experimental design. Experiments as an app.

## Part 1
These works together result in a human in the loop digital twin for simulating human workstations. It can also be used to design and compare the performance of workstation configurations.

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