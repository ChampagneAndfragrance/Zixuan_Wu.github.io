---
title: Hijacking Robot Teams Through Adversarial Communication
authors:
- admin
- Sean Charles Ye
- Byeolyi Han
- Matthew Gombolay
date: 2023-05-15
publishDate: '2023-01-01'
publication: '*7th Annual Conference on Robot Learning*'
publication_types:
- manuscript
abstract: Communication is often necessary for robot teams to collaborate and complete
  a decentralized task. Multi-agent reinforcement learning (MARL) systems allow agents
  to learn how to collaborate and communicate to complete a task. These domains are
  ubiquitous and include safety-critical domains such as wildfire fighting, traffic
  control, or search and rescue missions. However, critical vulnerabilities may arise
  in communication systems as jamming the signals can interrupt the robot team. This
  work presents a framework for applying black-box adversarial attacks to learned
  MARL policies by manipulating only the communication signals between agents. Our
  system only requires observations of MARL policies after training is complete, as
  this is more realistic than attacking the training process. To this end, we imitate
  a learned policy of the targeted agents without direct interaction with the environment
  or ground truth rewards. Instead, we infer the rewards by only observing the behavior
  of the targeted agents. Our framework reduces reward by 201% compared to an equivalent
  baseline method and also shows favorable results when deployed in real swarm robots.
  Our novel attack methodology within MARL systems contributes to the field by enhancing
  our understanding on the reliability of multi-agent systems.
---
