# TF_AZURE_UBUNTU
Terraform create Ubuntu VM in Azure


Create Ubuntu 18 Virtual Machine in AZURE

    Create a virtual network
    Create a subnet
    Create a public IP address
    Create a network security group and SSH inbound rule
    Create a virtual network interface card
    Connect the network security group to the network interface
    Create a storage account for boot diagnostics
    Create SSH key
    Create a virtual machine

Tested with:
AzureRM 3.11 https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs
Terraform 1.2.0 https://www.terraform.io/downloads


RUN:
    terraform init
    terraform plan -out main.tfplan
    terraform apply main.tfplan
