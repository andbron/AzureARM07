This template creates 2 Virtual Machines in an Availability Set and deploys/configures a load balancer with NAT rules. 

The template also deploys a Storage Account, Public IP address and Network Interfaces but uses an existing Resource Group

for vNet and subnet as follows:

Resource Group - andbron-austse-rg-vnet01
vNet - andbron-austse-vnet01
Subnet - ab-subnet-vm-tmp01

In this template, we use the resource loops capability to create the network interfaces and virtual machines

The configuration file uses the following....

Resource Group - andbron-austse-rg-ARM07 (manually add tags - AutoShutdownSchedule) 

Storage Account - andbronstorAzureARM07 

Existing Subnet - ab-subnet-vm-tmp01

JSON Template - AzureARM07 variables
