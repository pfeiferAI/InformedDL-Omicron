#  InformedDL-Omicron  
An informed deep learning model for analyzing the Omicron wave and assessing the impact of vaccination.

##  Overview  
The **InformedDL-Omicron** project utilizes **Physics-Informed Neural Networks (PINNs) [1](#1)** and **Disease-Informed Neural Networks (DINNs)[2](#2)** to model the **Omicron variant spread** and its epidemiological dynamics in Germany, France, and Italy.

By integrating **real-world COVID-19 data** with **epidemiological constraints**, this model dynamically estimates **transmission rates (β), reinfection rates (η), vaccine efficacy (δ),** and other key parameters, while ensuring physically meaningful solutions.

---
[1]: Raissi, Maziar, Paris Perdikaris, and George E. Karniadakis. "Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations." Journal of Computational physics 378 (2019): 686-707.

[2] Shaier, Sagi, Maziar Raissi, and Padmanabhan Seshaiyer. "Data-driven approaches for predicting spread of infectious diseases through DINNs: Disease Informed Neural Networks." arXiv preprint arXiv:2110.05445 (2021).

###  Key Contributions  
- Developed a **DINN model with sliding-window approach** to understand the dynamic behavior of Omicron wave and **real-time estimation of epidemic parameters**.
- Assessed the **impact of vaccination and mutations on Omicron transmission**.  

---

##  Citation  
If you use this repository in your work, please cite the following:  

E. Shamsara, F. König, N. Pfeifer, "An Informed Deep Learning Model of the Omicron Wave and the Impact of Vaccination". Computers in Biology and Medicine (2025)


  


