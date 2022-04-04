---
layout: page
title: Projects
permalink: /projects/
---

__Page under construction__ 

Please see [https://github.com/nphamilton](https://github.com/nphamilton) to see some of the projects I have worked on in the last couple of years. I will be adding detailed descriptions soon.

# Research Summary

During my time with the Verification and Validation of Intelligent and Trustworthy Autonomy Laboratory ([VeriVITAL](http://www.verivital.com/)), my research has focused on the development of safe and robust Machine Learning (ML) controllers for various Cyber-Physical Systems (CPS). In my studies, I found Reinforcement Learning (RL) to be the most promising ML approach. Thus, most of the work listed below has to do with RL.


## [stl-gym](https://github.com/nphamilton/stl-gym)

__A tool for monitoring Signal Temporal Logic (STL) specifications in OpenAI Gym environments and replacing the reward function with the degree of robustness.__

This project is still under development.

## [mlv_2020_project](https://github.com/nphamilton/mlv_2020_project)

__A project focused on uncovering how safe Safe Reinforcement Learning approaches are by formally verifying the trained network.__

This project inspired many of my later works in comparing different Safe Reinforcement Learning approaches. Here, I wanted to formally verify the trained networks created using a method from an award-winning paper. In the process of re-creating their results, _using their code_, I found inconsistencies in how they compared their approach to previous ones. When I accounted for these inconsistencies, I found all the claims that their approach speeds up the training process were unfounded. Instead, all the performance gains were the result of simplifying the tasks for their agents.

I outlined everything I did in [this write-up](/assets/papers/ML_Verification_Project.pdf) and will link the blog post describing a lot of the takeaways when I've finished writing it.

## [rl_library](https://github.com/nphamilton/rl_library)

__A collection of RL algorithms and training applications I wrote.__

I started this project in an attempt to create understandable RL algorithms. I started this before stable-baselines made a commitment to maintaining good documentation and before SpinningUp was released. The main advantage for continuing to use these implementations is when training agents in ROS applications. 