# Lab 4 - Azure Virtual Network & VM-to-VM Communication

**What i did:** Created an Azure Virtual Network (VNet) and deployed two Ubuntu 24.04 LTS VMs (vm-web and vm-app) into the same VNet. SSH'd into vm-app via. Cloud Shell and used the ping command to communicate with vm-web using its private IP address, proving successful private network communication. Stopped both VMs immediately after the lab

**What i learned:** A Virtual Network (VNet) is Azure's private network, resources inside it communicate securely without going over the public internet. Subnets divide the VNet address space into smaller segments. VMs in the same VNet can communicate by private IP by default and private IPs are assigned automatically

**Services used:** Azure Virtual Networks, Subnets, Private IP addressing, Network isolation, NSGs, Azure networking defaults
