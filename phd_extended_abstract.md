# Data-based Inclusion of Humans into Cyber-Physical Manufacturing Assembly Systems

Manufacturing assembly is a major indicator of a country's economic growth. Humans remain a crucial resource in assembly due to their flexibility. Human inclusion in smart manufacturing, cyber-physical production systems, and assembly has received a sharp increase in interest due to economic and social changes.

Human fatigue is an important consideration as it affects both production outputs and human health. In fact, we cannot measure fatigue directly, only the effects thereof. It affects a system's throughput rate, quality output, where a high level increase the risk of injury and long-term health issues. Two methods of data acquisition are human signals and production signals. Human signals have seen commercial success in static tasks like pilots and long-distance drivers, but are impractical in a flexible environment like manufacturing assembly.

## Part 1: Digital Twin Human Workstation

To address these issues, a human-in-the-loop digital twin is developed for simulating human workstations. It can also be used to design and compare the performance of workstation configurations.

## Chapter 1: VR Verification by Observation

The insight is that by using VR, we can postpone many of the data acquisition challenges. The issue then becomes confirming that VR simulations are suitable for measuring these production signals. This study simulates a series of tasks and confirms that VR can observe fatigue-related phenomena. This work was presented at a conference[^0].

### Results

The VR simulation results show that we can observe the throughput rate predicted by Wright-learning and quality risk index.

### Implications

The data obtained can be used to construct human performance models. This allows comparing the performance of human workstations and workschedule performance.

## Chapter 2: Active Experiment Design

Human trials are time-consuming, costly, and labor-intensive. This work investigates experimental design as it has the potential to reduce the number of trials conducted by suggesting informative samples. Few previous works consider VR human experiment systems using linear models and conducting offline experimental design. The proposed solution uses an online deep learning model. This work has been accepted for journal publication[^1].

### Results

When compared to random sampling, this method significantly reduces the number of trials.

### Implications

This solution uses online experimental design, resulting in automated VR experiments. When combined with the previous works, this enables remote, concurrent, and automated experimental design. Experiments as an app.

## Part 2: Active control of human workstations

The method previously used for experimental design can be extended to optimize operation (control),  i.e. Bayesian Optimization. This investigation starts b showing how this method of active-learning can be applied to controlling industrial processes, throught a simulated case study, deploying the developement of application specific constraints. To ethically control a human workstation, we will need to consider human fatigue levels. In the next chapter we develop a model with the capabilities to estimate human fatigue.

## Chapter 3: Active control of industrial systems:

Active learning methods have been used for industrial applications for parameter tuning such as selecting laser welding characteristics. Here we propose using it for automated modeling and control of industrial processes with the aim of later applying it to human workstation processes. This work investigates applying deep active learning to control Industrial systems. As such, a  case study is selected to simulatie developing custom constraints. Specifically a heat transfer problem is formulated where unconstrained exploration results in extreme temperatire fluxtuations.  In this case reducing fluctuation could reduce system wear and therefore maintenance. Distance  based constraints are developed to limit fluxations during exploration. 

This work has passed abstract review for an international conference [^2].

### Results 

When comparing constrained and unconstrained, constrained exploration resulted in less fluxation during exploration while reaching the same optimal operating conditions. 

### Implications

This methods is able to automate modeling and control and therefore can be useful for automating control of systems with  regularly changing dynamics. The case study shows that the method is flexible allowing developed of application specific constraints. 

## Chapter 4: Estimating human states

This work developed a model based on the requirement of extracting human fatigue. The aim is top extract human states like fatigue from production and human signals using unsupervised learning techniques via an auto-encoder. Blind source separation (BSS) is problem formulation that typically uses linear algebra for signal processing and audio sources separation. Here we argue that deep image processing and human state estimation can be viewed as BSS problem. By doing so we gain insights into developing a non-linear dynamic (time-varying with hidden state interaction) model. Several simulations are conducted to investigate if the model can estimate the source (hidden state). This work has been peer reviewed and will be presented in a conference[^3].

### Results

These model successfully estimated sources of symmetric, non-symmertric, and non-smooth signals. Making it suitable for estimating human based on production signals.

### Implications 

Formulating several problems as BSS problems allowed combining insight of linear algebra with modern deep learning techniques. A model meeting the requirements of human state estimation was developed. The auto-encoder selected requires more sensors than hidden states, this is a reasonable constraint as redundant sensors are typical in industrial application.

# Conclusion

This work investigated including humans into modern production systems  using manufacturing assembly as a challenge. We provide a development  path from data acquisition to data-based modeling and arriving at  data-based control. We tackle the challenges of human data acquisition  by employing a VR-digital twin. Combining this with active learning for  experimental design, we can accelerate the generation of predictive  models by automating experiments and reducing the number of experimental trials. To tackle control, we show that it is possible to extend this  method to industrial control applications and develop a model capable of estimating human hidden states. This work contributes to the advancement of human-centric production  systems and paves the way for future research in this field.



Candidate: [Clint Alex Steed](README.md)

Supervisor: [Namhun Kim](https://scholar.google.com/citations?user=0dlS09UAAAAJ)

[^0]: Steed, C. A., & Kim, N. Investigating the relationship between production quality and human fatigue. *International Federation of Operational Research Societies (IFORS 2021)*.
[^1]: Steed, C. A., Kim, N. (2023, **Accepted**). Deep active-learning based model-synchronization of digital manufacturing stations using human-in-the-loop simulation. Journal of Manufacturing Systems. [preprint](Docs/SMEJMS-D-22-01279.pdf)
[^2]: Steed, C. A., &#38; Kim, N. (2023, **Under Review**). Automated modeling and control of steady state processes using active learning, [live version](https://github.com/Acadevic/Active-control). <i>2nd International conference on Industrial Systems and Management Engineering ISEM2023 </i>.
[^3]: Steed, C. A., &#38; Kim, N. (2023, **Accepted**). Unsupervised hidden state estimation as blind source separation using Auto-encoder RNN filter. <i>15th International Conference on Advanced Computational Intelligence ICACI2023</i> [preprint](Docs/Autoencoder-rnn_filtering.pdf) 