---
title: Distributed Q-Learning
summary: 
  DistQL is a parallel, distributed, reinforcement learning system. 
authors:
- max
tags:
- Reinforcement Learning 
- Paper
date: "2022-02-25T00:00:00Z"
draft: false

# Optional external URL for project (replaces project detail page).
# external_link: https://github.com/MaxRobinson/DistributedQMemory

links:
- icon: github
  icon_pack: fab
  name: Check it out
  url: https://github.com/MaxRobinson/DistributedQMemory
url_code: "https://github.com/MaxRobinson/DistributedQMemory/tree/master/DistQL"
url_pdf: "https://github.com/MaxRobinson/DistributedQMemory/blob/master/DistQL-Paper/DistributedQLearning.pdf"
url_slides: ""
url_video: ""


image:
  caption: Photo by NASA on Unsplash
  focal_point: Center
---

## Abstract 
Reinforcement learning can take single agents many sequential episodes in order to
learn. To decrease the number of episodes a single agent must complete to attain a desired
performance, researchers have looked to parallel learning architectures. DistQL is a parallel,
distributed, reinforcement learning system. The system uses multiple agent-environment
pairs, where agents can learn in parallel to each other and update a central QServer. DistQL
was applied to two environments. The results showed that it is possible to have a large
decrease in the number of episodes need for an agent to perform well compared to a single
agent, as the number of distributed agents increases.
