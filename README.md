# Introduction to Containerization and Orchestration

Today we will focus on familiarization with industry-standard containerization
and orchestration technologies. Particularly, we will focus on Docker for
containerization and Docker Compose, Docker Swarm, and Kubernetes for
orchestration.

## Some questions to consider:
- Explain the role of layers and inheritance in creating Docker images.
- What is the distinction between networking containers using links and
using networks?
- Why might it be an advantage to utilize orchestration for production
infrastructure as opposed to writing a script that sets up Docker
networking between containers?
- What are the distinctions between Docker Compose and Docker Swarm?
- Explain the basic functionality of `minikube`.
- What are the security advantages of using Kubernetes as opposed to
Docker Swarm in a production environment?
- What is the distinction between a pod and a deployment?
- What is the most general name for a Kubernetes resource that will
provision a public IP address and route incoming requests to a pod?

## Resources
You may find the following links helpful, in addition to each technology's
official documentation.

- https://www.katacoda.com/learn
  - Docker & Containers
    - Deploying Your First Docker Container
    - Building Container Images
    - Ignoring Files During Build
    - Creating Networks Between Containers Using Links
    - Creating Networks Between Containers Using Networks
    - Orchestration Using Docker Compose
    - Learn Docker Swarm 101
  - Kubernetes
    - Launch a Single Node Cluster
    - Launch a Multi-Node Cluster using kubeadm
    - Deploy Containers Using kubectl
    - Deploy Containers using YAML
    - Networking Introduction
- https://medium.com/google-cloud/kubernetes-101-pods-nodes-containers-and-clusters-c1509e409e16 (first in a series)