---
title: 'Case Studies'
draft: false
---

[Docker](https://www.docker.com/ "Docker") helps deploy small and lightweight execution environments which shares your operating system kernel but otherwise run in isolation from each other. It has helped popularize the concept of containerization.

![docker_vm](https://raw.githubusercontent.com/TART-MSU/HyperProb/gh-pages/docs/assets/images/docker_vm.png)
*Figure: Virtual machines vs Docker Container*

The above picture (borrowed from [here](https://www.docker.com/blog/containers-replacing-virtual-machines/ "docker_vs_vm"), read the post for an elaborate explaination). The idea is that from a docker image, we can create several containers, which will run in isolation by mainly using our host operating system.

We chose this solution to deploy the tool so that the users can avoid the installation process for the dependencies, that have already been included in our docker image. 

