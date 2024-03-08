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
drag & drop screenshots here or use imgur and reference them using imgsrc

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*
