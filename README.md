# PfSense-Firewall-Project

## Objective

Installation and configuration of pfsense firewall. This is the security solution that helps protect our perimeter, a device that can allow or deny traffic from coming in and out. Simply put, you can much think of this as a bouncer at a club.
This particular project is very straight forward, and one of the reasons why this is needed is for the protection of our network security. Protect the network by controlling incoming and outgoing traffic based on predetermined security rules. pfSense can act as a firewall to safeguard against unauthorized access and potential threats.

### Skills Learned

- Understand how to create, configure, and manage virtual machines, including allocating resources like CPU, memory, and storage.
- Gain knowledge about IP address configuration, subnet masks, and gateway settings.
- Learn how to assign and configure network interfaces (WAN, LAN, etc.).
- Learn to create and manage firewall rules to control incoming and outgoing traffic based on IP addresses, ports, and protocols.
- Learn how to install an operating system (pfSense) on a virtual machine.
- Understand best practices for securing a network firewall, including regular updates and patch management.

### Tools Used

- Virtualization Software: Oracle VM VirtualBox
- pfSense ISO Image: pfSense Download: The installation ISO file for pfSense, which can be downloaded from the official pfSense website.
- pfSense Web GUI: The primary interface for configuring and managing pfSense, accessed via a web browser.
- Host Operating System: The operating system running on the physical machine hosting the virtualization software.
- Web Browser: Used to access the pfSense web-based GUI for configuration and management.

## Steps
Setup Virtual Machine:

Choose a hypervisor (e.g., VMware, VirtualBox, Hyper-V).
Create a new virtual machine with sufficient resources (CPU, RAM, storage).

Installation of pfSense:

Download the pfSense ISO file.
Attach the ISO to the VM and boot from it.
Follow the installation prompts to install pfSense on the VM.

Initial Configuration:

Assign network interfaces (e.g., WAN and LAN).
Set IP addresses for the interfaces.
Configure basic settings like hostname, domain, and DNS servers.
Firewall Rules and NAT:

Create firewall rules to control traffic flow.
Set up NAT rules to manage IP address translation.
Services and Features:

Configure additional services like DHCP, DNS, and VPN.
Install and configure packages for added functionality (e.g., Snort for IDS/IPS, Squid for web proxy).
Testing and Monitoring:

Test the configuration to ensure it meets the network's security and performance requirements.
Monitor the system using pfSense’s built-in tools and logs.
By following these steps and focusing on these objectives, pfSense can be effectively deployed on a virtual machine to manage and secure a network environment.

Images from the lap to follow soon!
