# Docker - SRIN Take-Home Assignments

### **What Docker tried to solve, what's useful about Docker for us.**

Tech stacks have versions where the app depends on. It runs in an environment, which can differ a lot in the operating system, versions, etc. This needs to be solved, tech stacks needs to work the same way on different environments so that there will be no more “but it works on my machine”. This is what docker trying to solve. In Docker, services manage their dependencies for themselves, bundled within its container. We also can change the underlying operating system without affecting the way it works.

### What Docker Image, Docker Containers and Docker Registry means.

**Docker images** are used to execute code in a container. They are like a set of instructions within a Docker container. Docker images also act as the starting point when using Docker. An image is comparable to a snapshot in virtual machine (VM) environments.

**A container** is a unit in software development which can package codes and all of their dependencies so that the app can run from one to another environments where developers work without any trouble. 

**A Docker registry** is a storage and distribution system for Docker images. In docker, one image may have multiple version, and registries are organized in Docker repositories where they hold all of those multiple version of the image.
