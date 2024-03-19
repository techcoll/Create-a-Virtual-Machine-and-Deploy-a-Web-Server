# Create-a-Virtual-Machine-and-Deploy-a-Web-Server

## Objective

I created a Virtual Machine in Azure to deploy a web server, specifically a Nextcloud server. I explored how the basic architecture of Azure works, by creating a Virtual Machine, connecting it to a subnet, protected by inbound and outbound rules thanks to Network Security Groups, in a Virtual Network. I used Bastion to connect to the machine via SSH, without exposing an external port to the Internet, and then installing a simple Nextcloud server and made the Virtual Machine available to me by opening a public IP and a DNS label.Note: before taking this Guided Project, if you don't have an Azure subscription yet, please create an Azure Free Trial beforehand at https://portal.azure.com.


### Skills Learned

- I learnt how to Create a Resource Group,
- Virtual Network and a subnet,
- Protect a subnet using a Network Security Group,
- Deploy Bastion to connect to a Virtual Machine,
- Create an Ubuntu Server Virtual Machine,
- Install Nextcloud by connecting via SSH using Bastion,
- Publish an IP,
- Create a DNS label.

### Tools Used

- Azure Portal: Azure's web-based management portal allows you to create and manage virtual machines easily through a graphical interface.
- Azure CLI: The Azure Command-Line Interface (CLI) is a powerful tool that allows you to manage Azure resources from the command line.
- Azure Resource Manager (ARM) Templates: ARM templates are JSON files that define the resources you want to deploy in Azure. 

## Steps

*Ref 1: Create Microsoft Azure account in https://portal.azure.com/*
![microsoft azure portal](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/c9acdf19-8883-4e48-a53f-bce1497b3e97)

*Ref 2: Create a Resource Group inside the Azure Portal*
![reource group2](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/76911369-dbcb-4c98-8a9f-42e1d8d3238e)

*Ref 3: Create a Virtual Network and a Subnet*
![Virtual network b](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/2cf545f9-5060-4d1c-b71e-ff1030742956)

*Ref 4: Protect a Subnet using a Network Security Group*
![NSG B 3](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/6f4ed54e-33b1-4739-8d7e-e53d31c76708)
![network security group 3](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/908672f2-7d07-4f4b-a90d-9e873e0002a4)

*Ref 5:Create and Deploy Bastion to connect to a Virtual Machine*
This will helip us to connect to our virtual Machine.
![BASTION deploy 4](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/5915945a-9f9b-420f-b465-745219d7c2c0)
![bastion 4b](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/14c5640b-23b1-4910-884b-2d84066a0407)

*Ref 6: Create an Ubutu server virtual machine*
![image](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/c93d5718-ec71-49ba-abef-593a41ccbe66)

*Ref 7: Install Nextcloud by connecting via SSH using Bastion*
![installing nextcloud](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/4b82ae4c-275a-4b2b-b4cf-e92a5d188ed2)
![install nextcloud by ssh](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/969ec0f8-4079-4e2d-8003-4c678595dd90)

*Ref 8: Publish an IP(Accessing the Nextcloud Instance on the web)*
![image](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/3b02781e-bc2e-4656-90d8-0d730a01d986)

*Ref 9: Create a DNS Label*
![9a](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/bf42d772-79b3-4d55-b9ad-50f6dba6d77b)

![image](https://github.com/techcoll/Create-a-Virtual-Machine-and-Deploy-a-Web-Server/assets/107801057/73df1dab-7088-4cfa-9f21-8b7c26526e79)

