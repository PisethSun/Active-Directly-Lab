# Active-Directly-Lab
Active-Directly Lab using Azure VM


Step 1: Create Domain VM
Create a users - Note: write down the username and password
Create Resiurce Group Name It- AD-LAB
Create VM01- Domain Controller (DC-1) - 2 CPU - with Window server 2022. Once the VM up and running, follow the next step
- Make sure you make IP to STATIC :
    -On Azure search Virtual Machine, Click on VM you just created (DC-1)
    - Under "Setting" click on Networking tab-> Click on NIC(Network Interface Card)->IP configuration -> Chnage Dynamic to Static-> SAVE.


Step 1: Create Cilent01 VM

Create VM01- Domain Controller - 2 CPU - with Window 10 Pro
Create a users - Note: write down the username and password
Make sure choose the correct resource group (example: AD-LAB-vnet)
Leave the subnet same and the rest are default
- Make sure THE Region of the DC-01 and Client-01  in the same region and resource group and Vnet ( Double check virtual network /subnet of both machine are the same).

Step 3: Allowed CSMP Protocol for both machine
