---
title: Learning Diverse Robot Striking Motions with Diffusion Models and Kinematically
  Constrained Gradient Guidance
authors:
- Kin Man Lee
- Sean Ye
- Qingyu Xiao
- admin
- Zulfiqar Zaidi
- David B D'Ambrosio
- Pannag R Sanketi
- Matthew Gombolay
date: 2025-05-15
publishDate: '2025-05-14T03:19:43.977294Z'
publication: '*IEEE International Conference on Robotics and Automation (ICRA)*'
publication_types:
- manuscript
abstract: 'Advances in robot learning have enabled robots to generate skills for a
  variety of tasks. Yet, robot learning is typically sample inefficient, struggles
  to learn from data sources exhibiting varied behaviors, and does not naturally incorporate
  constraints. These properties are critical for fast, agile tasks such as playing
  table tennis. Modern techniques for learning from demonstration improve sample efficiency
  and scale to diverse data, but are rarely evaluated on agile tasks. In the case
  of reinforcement learning, achieving good performance requires training on high-fidelity
  simulators. To overcome these limitations, we develop a novel diffusion modeling
  approach that is offline, constraint-guided, and expressive of diverse agile behaviors.
  The key to our approach is a kinematic constraint gradient guidance (KCGG) technique
  that computes gradients through both the forward kinematics of the robot arm and
  the diffusion model to direct the sampling process. KCGG minimizes the cost of violating
  constraints while simultaneously keeping the sampled trajectory in-distribution
  of the training data. We demonstrate the effectiveness of our approach for time-critical
  robotic tasks by evaluating KCGG in two challenging domains: simulated air hockey
  and real table tennis. In simulated air hockey, we achieved a 25.4% increase in
  block rate, while in table tennis, we saw a 17.3% increase in success rate compared
  to imitation learning baselines.'
---
