# Best practices with Azure and Kubernetes

## Why do we need this?

We are going digital: by 2020:

- 1 mil new devices online / hour
- S&P 500 company mean age will be 12 
- 60% of computing will be in public cloud
'
IT has to deal with threats, reliancy, and innovation in a time constrained environments

Think of the cloud as the new Data Center! They map pretty well 

> DevOps is the union of people, process, and products to enable the continuous delivery of value to our end users - Donovan Brown


## So what is Kubernetes anyways?
- When something fails, it's not really down

Kubernetes helps make your nodes failure friendly

Kubernetes is the de-facto orchestrator
- portable
- extensible
- self-healing

## AKS - what is it?
AKS = Your kubernetes cluster on Azure

- Easy to use
    - 3 commands to start
- Easy to manage
- Uses open APIs
    - No forks from kubernetes (real deal)

    az aks create -g resource -n cluster --generate-ssh-keys

    az aks install-cli // install cli

    az aks get-credentials -g resource -n cluster // Get creds for auth

    kubeclt get nodes // get the running nodes

    az aks list -o table
    
    az aks upgrade -g resource -n cluster --kubernetes-version 1.8.1
    
    ..etc

AKS provides management to abstract the challenges of operating a cluster

### AKS makes the control plane free!

## Release automation tools

- draft
    - streamlines release and dev
- helm
    - package manager for kubernetes
- brigade
- kashti

### Draft

Simplifies app dev and deloyment into cluster

Using 2 simple commands, developers can now behin hacking on container-based apps without requiring docker or even installing kubernetes themselves

Language support - draft creates dockerfiles and helm charts with best practices for that language

--- 
#### Demo of Draft & helm collaboration

Minimum set of knowledge:

- Containers: virtualize OS
- Docker - Runs containers
- Kubernetes - Orchestrator
- Helm - package manager for k8s
- Draft - Dev tool to make container dev easier
    - Auto creates my docker file
    - helm charts
    - simplifies workflow for inner dev loop

Draft dev flow:

- Create project `draft create`
- Edit code
- `draft up`
- `draft connect` or `draft debug`

Then normal CI/CD

---

## WTH is Help

Helm is **DEATH TO COPY PASTE** and **NO MORE INDENT ERRORS***

I gave up taking notes here.. sorry :()


---
Resources:

**#LoECDA** - tag them on twitter for help with Cloud Dev Ops

**[helm](heml.sh)**

**[draft](draft.sh)**