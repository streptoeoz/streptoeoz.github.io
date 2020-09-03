---
caption:
  title: Project 2
  subtitle: Learning Based Sampling for RRT*
  thumbnail: assets/img/2.jpg

title: Learning Based Sampling for RRT*
subtitle: RRT*, Conditional Variational Autoencoder (CVAE), Machine Learning
image: assets/img/projects/rrt1.png
alt: image alt text

---
Compared with traditional uniformly sampled path planning approaches, a biased sampling method which learns from demonstrations and environmental restrictions would be preferable due to its efficiency and generality, as it can capture the obstacles and some sense of dynamics in the system. In this project, we have combined RRT∗ algorithm and a conditional variational autoencoder (CVAE) trained to learn from the latent dimensions and propose samples accordingly. We have generated and trained on our own datasets, including 4 maps and 26985 sampling states. The sampling states are generated with hybrid A*. <br>

Assuming latent variables are Gaussian, the CVAE is trained to maximize the conditional log likelihood. The network contains a three-layer encoder and a three-layer decoder. The input to the encoder includes the grid obstacle map, successful planning states, intial and end point of the trajectory. In the offline test phase, only the decoder is utilized. <br>

The modified planning algorithms are then applied on the vehicle parking path planning, and compared with the uniformly sampled RRT∗ and bi-RRT∗. A substantial boost is observed in path planning performance with this inclusion of biased sampling network. For RRT∗, the number of nodes extended, elapsed time and path length have dropped by 72.5%, 91.4% and 18.0% respectively. For bi-RRT∗, they have dropped by 55.1%, 70.4% and 17.7% respectively.

<!-- {:.list-inline}
- Date: January 2017
- Client: Threads
- Category: Illustration -->

