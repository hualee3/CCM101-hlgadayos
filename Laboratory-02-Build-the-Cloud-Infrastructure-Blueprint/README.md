# Laboratory 2: Build the Cloud Infrastructure Blueprint

## Mission Overview
Congratulations,
Your onboarding has been successfully completed, and your Cloud Computing Portfolio has been approved by
your supervisor.
CloudNova Technologies has now assigned you to your first official project.
Before deploying cloud services, every cloud engineer must understand the infrastructure that powers modern
cloud computing. Your mission is to investigate the components of cloud infrastructure, identify how compute,
storage, networking, and identity services work together, and document your findings as if you were preparing
technical documentation for a client.
Using the KillerCoda Playground, Linux tools, official cloud documentation, and your GitHub Cloud Computing
Portfolio, you will complete a series of engineering tasks that simulate the planning phase of a cloud deployment.

## Objectives
At the end of this laboratory activity, you should be able to: 
- Explain the major components of cloud infrastructure.
- Investigate the hardware and software resources available in a Linux environment.
- Differentiate compute, storage, networking, and identity resources.
- Interpret the relationship between cloud infrastructure components.
- Create professional technical documentation using Markdown.
- Continue building a structured GitHub Cloud Computing Portfolio.

## Cloud Infrastructure Components
The following cloud infrastructure components were identified and observed during the lab. See `cloud-components.md` for full detail:
- **Compute** — the virtual CPU and memory allocated to the KillerCoda VM.
- **Storage** — the `/dev/vda1` disk used as the main storage of the virtual machine.
- **Networking** — the VM's private IP address and internal Docker bridge network.
- **Operating System** — Ubuntu 24.04.4 LTS running on kernel 6.8.0-138-generic.

## Tools Used
- KillerCoda Playground (Ubuntu 24.04 Linux terminal)
- GitHub (version control and portfolio hosting)
- Markdown (documentation)
- Diagramming tool (for the cloud architecture diagram)

## Linux Commands Executed
| Command | Purpose |
|---|---|
| `cat /etc/os-release` | View OS name and version |
| `uname -r` | View kernel version |
| `lscpu` | View CPU model, architecture, and core count |
| `nproc` | Count available CPU cores |
| `free -h` | View total/used/free RAM and swap |
| `df -h` | View disk capacity and usage per filesystem |
| `mount` | List mounted filesystems |
| `hostname` | View the machine's hostname |
| `hostname -I` | View assigned IP address(es) |

## Skills Learned
- Using basic Linux commands to check the system's hardware and software.
- Understanding how the system information, such as CPU, RAM, storage, and network, relates to cloud resources like compute, storage, and networking.
- Comparing similar cloud services from AWS, Azure, and GCP.
- Designing a simple cloud architecture diagram.
- Writing clear and organized documentation using Markdown.

## Challenges Encountered
Understanding the command outputs, such as the virtualization details from `lscpu` and the two IP addresses from `hostname -I`, was challenging at first. I had to understand what each result meant and how it connects to cloud computing instead of just copying the terminal output directly.