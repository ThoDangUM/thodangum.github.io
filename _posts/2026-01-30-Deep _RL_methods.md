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

<!--more-->

# **DDPG (Deep Deterministic Policy Gradient)**

DDPG is a combination between DQN (Deep-Q Network) and DPG (Deep Policy Gradient). DDPG can be used for systems which have continuous space.

First, we introduce DQN. DQN is Q-learning using deep network.  

# **PPO (Proximal Policy Optimization)**

PPO is one of policy gradient methods. It is stability, reliability, easy to implement and sample efficiency. This derives from introducing a new novel objective function that allows to update gradient with multiple epochs (multiple epochs of stochastic gradient ascent)  (different from standard policy gradient methods which perform one gradient update per data sample).

First, we introduce the probability ratio between new policy and old policy:

$$
\begin{equation} 
  r(\theta) = \frac{\pi_{\theta}(a,s)}{\pi_{\theta_{old}}(a,s)} 
\end{equation}
$$

The objective function is defined as:

$$
\begin{equation} 
  J^{CLIP}(\theta) = \mathbb{E}[min(r(\theta),\hat{A}(a,s),clip(r(\theta),1-\epsilon,1+\epsilon)\hat{A}(a,s))] 
\end{equation}
$$




The objective function with KL divergence is defined as:

$$
\begin{equation} 
  J^{KL,CLIP}(\theta) = ??
\end{equation}
$$

