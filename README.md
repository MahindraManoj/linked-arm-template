# linked-arm-template

Prerequisites:

1.	An Azure subscription
2.	A resource group with a virtual network needs to be installed.
3.	The subnet/network address must have enough Ips to allocate to the load balancer front-end and the cluster nodes.
The main template deploys multiple windows server 2019 DC VMs with a max. of 5 data disks to each vm. It also provisions a basic internal load balancer.
