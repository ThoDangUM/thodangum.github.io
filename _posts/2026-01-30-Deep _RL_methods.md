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

First, we introduce the probability ratio between new policy and old policy:

$$\begin{equation} 
  r(\theta) = \frac{\pi_{\theta}(a,s)}{\pi_{\theta_{old}}(a,s)} 
\end{equation}
$$

The objective function is defined as: please consider

$\begin{equation} 
  J(\theta) = E() 
\end{equation}
$


