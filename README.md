# networkwalks-BO82-week1-Cybersecurity-lab-setup
This project documents the setup of a virtual cybersecurity laboratory environment for hands-on security testing and learning.

The objective of Week 1 was to prepare an isolated virtual environment using VirtualBox and Kali Linux, configure a dedicated NAT Network, assign the required network configuration, and create a VM snapshot to provide a restore point for future cybersecurity labs.


Step 1 — Install 7-Zip

7-Zip was installed to extract and manage compressed files associated with the virtual machine.

Official Website:
https://7-zip.org/download.html

Step 2 — Install VirtualBox

Oracle VirtualBox was installed to provide the virtualization environment required to run Kali Linux.

Official Website:
https://www.virtualbox.org/wiki/Downloads

Step 3 — Configure the VirtualBox NAT Network

A dedicated NAT Network was created in VirtualBox using the following subnet:

Network: 10.0.0.0/24

This provides a private network for communication between virtual machines while maintaining separation from the host network.

Step 4 — Download & Import Kali Linux

Kali Linux was downloaded and imported into VirtualBox as the primary cybersecurity laboratory machine.

Official Kali Linux Website:
https://www.kali.org/get-kali/

Kali Linux provides a wide range of tools used for cybersecurity activities such as network reconnaissance, vulnerability assessment, penetration testing, and security analysis.

Step 5 — Configure Kali Linux Networking

After importing Kali Linux, its network adapter was configured to use the newly created VirtualBox NAT Network.

The network configuration was then checked from within Kali Linux to verify that the virtual machine was correctly connected to the lab network.

Step 6 — Create a Virtual Machine Snapshot

After successfully completing the Kali Linux configuration, a VirtualBox snapshot was created.

The snapshot provides a restore point that allows the virtual machine to be returned to its working state if future cybersecurity experiments cause configuration changes or problems.
