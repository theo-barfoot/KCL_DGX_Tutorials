# BMEIS DGX Tutorials

## Introduction

The School of BMEIS AI cluster is a system made of the following components:

* 3 x Dell PowerEdge headnodes running Ubuntu (currently 20.04)
* 2 x Nvidia DGX2 work nodes with 16 GPUs each
* 4 x Nvidia DGX A100 worker nodes with 8 GPUs each
* A NetApp AFF800 all-flash storage with 512TB of space

The DGX1, DGX2 and NetApp AFF8000 are 3+ years old (as of December 2022) and out of support, but they are still working
fine.
The 4 DGX A100 nodes are new and will be supported for 5 years.

The job scheduler is RunAI, a submission system based on Kubernetes, which is a system for deploying and managing
containerised applications.

Users wanting to use the cluster and submit jobs need to access one of the headnodes via ssh. To do this, new starters
need an account on the cluster. This can be requested by their supervisors sending an email to [*bmeis-it@kcl.ac.uk*](mailto:bmeis-it@kcl.ac.uk).


## Tutorials

1. [Setup Cluster Connection](1-Setup-cluster-connection)

    This tutorial covers the basic about the ssh connection with the cluster. Internal and external device connections are considered, using a bouncer. It helps to stablish a passwordless authentication using ssh-keys.
