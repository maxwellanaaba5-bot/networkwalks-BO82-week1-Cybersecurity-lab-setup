# networkwalks-BO82-week1-Cybersecurity-lab-setup
This project documents the setup of a virtual cybersecurity laboratory environment for hands-on security testing and learning.

The objective of Week 1 was to prepare an isolated virtual environment using VirtualBox and Kali Linux, configure a dedicated NAT Network, assign the required network configuration, and create a VM snapshot to provide a restore point for future cybersecurity labs.

Step 1 — Install 7-Zip
7-Zip was installed to extract and manage compressed files associated with the virtual machine.

Step 2 — Install VirtualBox
Oracle VirtualBox was installed to provide the virtualization environment required to run Kali Linux.

Step 3 — Configure the VirtualBox NAT Network
A dedicated NAT Network was created in VirtualBox using the following subnet:
Network: 10.0.0.0/24
This provides a private network for communication between virtual machines while maintaining separation from the host network.

Step 4 — Download & Import Kali Linux
Kali Linux was downloaded and imported into VirtualBox as the primary cybersecurity laboratory machine.

Step 5 — Configure Kali Linux Networking
After importing Kali Linux, its network adapter was configured to use the newly created VirtualBox NAT Network.
The network configuration was then checked from within Kali Linux.

Step 6 — Create a Virtual Machine Snapshot
After successfully configuring the Kali Linux environment, a VirtualBox snapshot was created.
The snapshot provides a restore point that can be used to return the virtual machine to its initial working state if a future cybersecurity experiment causes configuration problems.
