---
title: 'Deep reinforcement learning'
date: 2026-01-30
permalink: /posts/2026/Deep_RL_methods/
excerpt_separator: <!--more-->
usemath: true
tags:
  - ML
  - Deep reinforcement learning
  - policy gradient
---

Deep reinforcement learning has actractted many works in robotics. This post introduces some of them for robotics.

# **DDPG (Deep Deterministic Policy Gradient)**

DDPG is a combination between DQN (Deep-Q Network) and DPG (Deep Policy Gradient). DDPG can be used for systems which have continuous space.
First, we introduce DQN. DQN is Q-learning using deep network.  

# **PPO (Proximal Policy Optimization)**

As we know Euler’s fomula is very ubiquitous in mathematics, physics, and engineering. The fomula is as follows:

$$e^{i\theta}=\cos(\theta)+i\sin(\theta)$$

I never though how to prove this formula until seeing a simple proof with an interesting story behind in the book “Linear Algebra and Its Applications”, Gilbert Strang. One day there was a letter came to MIT from a prisoner in New York, asking if Euler’s fomula was true? It is really astonishing. Three key functions of mathematics come together in such a graceful way.

First, we introduce the probability ratio between new policy and old policy:
```math
r(\theta) = \frac{\pi_{\theta}(a,s)}{\pi_{\theta_old}(a,s)}
```

The objective function is defined as:
```math
J(\theta) = ?? 
```