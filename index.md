# Transfer Learning and Hierarchical RL Study Group
## Fall 2018/ Winter 2019

**URL**: https://mcgillmrl.github.io/transfer_club/

**Location**: MC 627 McConnell Engineering Building

**Time**: Fridays at 4:30 p.m.

Our study group is concerned with the following two topics:
- Transfer Learning in robotics
- Hierachical Reinforcement Learning in robotics

We think these two problems are crucial forpractical applications of learning algorithms in robotics since collecting data with real robots is expensive and the search space for policies in real robotics applications is generally too vast. Transfer learning refers to the area of machine learning concerned with the deployment of algorithms trained on a __source domain__ to perform tasks on a __target domain__. Hierarchical RL refers to the family of techniques where the solutions to a reinforcement learning problem, usually parametric policies, have a hierarchical structure and whose components may be deployed separately.

## Schedule
### Week 1 (October 26th) Introduction to Transfer Learning in Robotics
Presented by [Juan Camilo Gamboa Higuera](https://github.com/juancamilog). Slides: [pdf](presentations/week1_juan/transfer_club01.pdf) [pptx](presentations/week1_juan/ransfer_club01.pptx)

The purpose of this meeting is to give an overview of the different problem formulations for transfer learning in robotics applicaitons.
Recommended reading material:

 - [Transfer Learning for Reinforcement Learning Domains: A Survey](http://www.jmlr.org/papers/volume10/taylor09a/taylor09a.pdf)
 - [Reinforcement Learning with Multi-Fidelity Simulators](http://acl.mit.edu/papers/Cutler14_ICRA.pdf)
 - [Multi-Fidelity Reinforcement Learning with Gaussian Processes](https://arxiv.org/abs/1712.06489v1)
 - [Unsupervised Cross-Domain Transfer in Policy Gradien](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/viewFile/9916/9879)
 - [Taskonomy](http://taskonomy.stanford.edu/)

### Week 2 (November 2nd) Applied Transfer Learning techniques in Robotics
Presented by [Melissa Mozifian](https://melfm.github.io/about.html)

The purpose of this meeting is to dive into more promising Transfer techniques applied in robotics.
Recommended reading material:

 - [Learning Dexterous In-Hand Manipulation](https://arxiv.org/pdf/1808.00177.pdf)
 - [Model-Agnostic Meta-Learning for Fast Adaptation of Deep Networks](https://arxiv.org/pdf/1703.03400.pdf)

### Week 3 (November 9th) Introduction to Hierarchical Reinforcement Learning
Presented by [Monica Patel](https://github.com/monicaMRL)
There isn't one paper to summerise this topic so following is brief abstract of what I am planning to present.
This Presetation will follow the same format as Juan's presentation of week 1. We will explore more on question of "What to Transfer? How its related to Hierarchy?" Some of the What's are:
1) Control Policies: Options, Skills, Universal Options, Absctract Markov Decision Processes, Policy sketches.
2) Value Function: Universal Value Function Approximators.
3) Reward: Little introduction on "Intrinsic Motivation" and Hierarchy in rewards.
4) Task Parametrization: Hierarchy in lifelong long learning 

--> *Only if time permits and if it interests anyone: "Theory of Mind" (Cognitive Science)* We can also talk about this off-line!

### Week 4 (November 16th) TBA
Presented by [Auguste Lalande](https://github.com/augustelalande)

### Week 5 (November 23rd) TBA
Presented by [Sanjay Thakur](https://github.com/sanjaythakur)
