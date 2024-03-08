>>> 1--Tasks To Be Performed:
1. Deploy 2 VMs with Ubuntu and Apache2 installed
2. Change index.html to include the following text
a. “This is VM1” on VM1
b. “This is VM2” on VM2
3. Create a load balancer which will balance the traffic between these two

VMs  
>>> 2-- Tasks To Be Performed:
Create an application gateway with the following configuration:
a. /vm1 should point to VM1
b. /vm2 should point to VM2
>>> 3--Tasks To Be Performed:
1. For the two VMs deployed previously configure DNS for the public IPs of
the VM
>>> 4--Tasks To Be Performed:
1. Deploy 2 VMs in different regions
2. Balance the load on these VMs geographically
To accomplish this please use Azure Traffic Manager
>>> 5--Tasks To Be Performed:
1. Create a VM without public IP address
2. Connect to this VM using bastion host
