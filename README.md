This template creates 2 Virtual Machines in an Availability Set and deploys/configures a public facing 
load balancer with NAT rules. 

The template also deploys a Storage Account, Public IP address and Network Interfaces but uses an existing vNet and subnet (Resource Group).

Resource Group - andbron-austse-rg-vnet01
vNet - andbron-austse-vnet01
Subnet - ab-subnet-vm-tmp01

The template uses resource loops capability to create the network interfaces and virtual machines

