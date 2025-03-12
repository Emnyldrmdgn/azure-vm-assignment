# azure-vm-assignment
#Assignment: Set Up an Azure Virtual Machine 

*Objective

Create a basic Azure infrastructure using a free Azure account. This infrastructure should include:

*An Azure Virtual Machine (Windows Server)
*A Public IP Address for RDP access
*A Virtual Network with a default subnet
*An Azure Disk attached to the VM
*All resources grouped under a single Resource Group
#Steps to Complete

1- Create a Resource Group
Use the Azure Portal to create a new Resource Group.
![resource1](https://github.com/user-attachments/assets/cb6331c1-73b1-4da8-bfb7-1cbc3056272f)

---------------------------------------------------------------------------------------------------------------
2- Set Up a Virtual Network

Create a Virtual Network with a default subnet.
![vnetwork1](https://github.com/user-attachments/assets/3bb62a0e-27cd-42bd-b98e-3ede671db422)
![vnetwork2](https://github.com/user-attachments/assets/f19bb8af-50ce-4224-9f94-17867df44f9a)
![vnetwork3](https://github.com/user-attachments/assets/1353eb1a-96b2-403d-bf92-905e1bb50937)
![vnetwork4](https://github.com/user-attachments/assets/825cd504-12c6-4ffb-bcdf-73a923ebd7b8)
![vnetwork5](https://github.com/user-attachments/assets/4e80911e-02e1-4205-b435-fccad7d5c22f)

---------------------------------------------------------------------------------------------------------------
3- Deploy a Windows Virtual Machine

Choose a free-tier eligible Windows Server.
Assign a Public IP for RDP access.
Place the VM in the previously created Virtual Network.

4- Attach a Data Disk to the VM

Add an Azure Disk to the created Virtual Machine.

![vm1](https://github.com/user-attachments/assets/440620b3-85b4-4608-8bfb-9ae2a0ad8baf)
![vm2](https://github.com/user-attachments/assets/98643bc7-e1f5-4dd1-a38d-c2d3ed1ebb71)
![vm3](https://github.com/user-attachments/assets/58cbb4ac-bf46-48ee-8b77-2c76fa53a7d7)
![vm4](https://github.com/user-attachments/assets/3175fb20-2642-4930-bede-30f5b3d11b0a)
![vm5](https://github.com/user-attachments/assets/897bb0da-5b4a-4b66-93e2-8feaf47a011c)
![vm6](https://github.com/user-attachments/assets/e4f03a58-8883-4f67-9ba0-faa395075af0)
*In Progress

![vminprogress](https://github.com/user-attachments/assets/59c8aa54-8467-485d-93ce-676035634bd4)
![vmcomplete](https://github.com/user-attachments/assets/eceb6b81-e3c4-4d04-906c-842322a5e925)

---------------------------------------------------------------------------------------------------------
5- Connect to the VM

Use Remote Desktop Protocol (RDP) to connect to the VM using the public IP.

![vmarayuz](https://github.com/user-attachments/assets/7633123f-227b-41dd-b503-a9c192089db0)
![rdpindir](https://github.com/user-attachments/assets/9eae2544-18a0-424b-899d-c396062c5d0d)
![vmconnecting](https://github.com/user-attachments/assets/68d5ec74-3cd5-4d2a-9826-120a0db4cf86)

->My Virtual machine
![Capture](https://github.com/user-attachments/assets/3e324660-ece5-4278-a625-6280ce9812d4)
![Capture2](https://github.com/user-attachments/assets/4b0bdaa3-3345-4a3a-bc79-34c3fe75a6a3)

6- Optional: Clean Up Resources

Delete the Resource Group after completion to avoid unnecessary charges.

**If you want to avoid being charged, you can delete all resources:

1. **Azure Portal** → "Resource Groups"
2. Select `MyResourceGroupc12`.
3. Click the "Delete Resource Group" button.
