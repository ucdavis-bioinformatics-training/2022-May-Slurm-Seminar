# Introduction

![High Performance Computing at UC Davis](images/HPC-unit-signature.png)

# Introduction

## What this talk is

* Brief overview of the resources offered by the High Performance Computing
  Core Facility and the Bioinformatics Core

* How to get access

* Very brief introduction to cluster terminology and concepts

# Introduction

## What this talk isn't

* In-depth discussion of UNIX, clusters, or computing in general
* Finished!  (Welcome to the beta)

##

	"Talks are never finished, only due"

# Introduction

## Who are we?

* Nikhil Joshi
* Bioinformatics Programmer/Analyst, UC Davis Bioinformatics Core
* 30+ years programming experience, 15+ years at the Bioinformatics Core, software installer for Genome Center cluster.

* Mike Lewis
* Systems Achitect, HPC Core Facility (previously of the Genome Center)
* 25 years of experience managing UNIX at scale, 20 years of HPC cluster
  design and administration.

# Introduction

If you were plowing a field, which would you rather use: Two strong oxen 
or 1024 chickens?

--Seymour Cray

![](images/CrayXMP_Feathered.jpg)

# Introduction

## What is a cluster?

> - A collection of machines that work together


## Why use a cluster?

> - Chickens are cheaper than oxen
> - There is a limit on the size of a single ox
> - ... but try getting 1024 chickens to move in the same direction


# Cluster Terminology

* **Node**:
An individual computer in the cluster

* **Login (or head) node**:
The node users log in to and use to submit jobs.

* **Scheduler (and queue)**:
The entity that coordinates which jobs run at what time on which node(s)

* **CPU Core**:
A single processing unit

* **Thread**:
Processing unit that shares resources with other threads

* **Interconnect**:
The network connecting the nodes to each other and to the storage

* **Core (memory)**:
RAM

* **Swap**:
If RAM is exceeded, virtual memory will be used.  Using disk instead of RAM.
(Much slower)

* **Thrash**:
Competing processes swapping at the same time.

