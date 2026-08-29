# Cloud Infrastructure Components

This document identifies my observations and examples of the different cloud infrastructure components that I found while exploring the Linux environment

## 1. Compute Resources
Compute resources are the CPU and memory that let the system run and do work.

- **Purpose:** Provide the CPU and memory needed to run the system, applications, and services.
- **Why it is important in cloud computing:** It is important in cloud computing because it needs a CPU and memory to work. These can be added or reduced when needed.
- **Relate it to the Linux environment provided by KillerCoda:** In KillerCoda, the virtual machine has 1 CPU core and 1.9 GiB of RAM, like a small cloud VM used for testing.

## 2. Storage Resources
Storage resources are where files and data are kept.

- **Purpose:** They save files, apps, logs, and other data.
- **Why it is important in cloud computing:** It is important in cloud computing because it gives a place to store data, and storage can be increased when needed.
- **Relate it to the Linux environment provided by KillerCoda:** In KillerCoda, `/dev/vda1` is the 19 GB storage used for system files and data.

## 3. Networking Resources
Networking resources let devices and systems connect to each other.

- **Purpose:** They allow systems to talk to each other and to the internet.
- **Why it is important in cloud computing:** It is important in cloud computing because it allows systems to communicate, connect to the internet, and control access between resources.
- **Relate it to the Linux environment provided by KillerCoda:** In KillerCoda, 172.30.1.2 is used by the VM, while 172.17.0.1 is used by Docker. This shows how separate networks can work in the same environment.

## 4. Operating System
The operating system is the software that controls the whole machine.

- **Purpose:** It manages CPU, memory, storage, and network, and lets apps run.
- **Why it is important in cloud computing:** It is important in cloud computing because Every VM needs an OS to run software and manage the system.
- **Relate it to the Linux environment provided by KillerCoda:** In KillerCoda, the VM runs Ubuntu 24.04.4 LTS with kernel 6.8.0-138-generic.