# Ansible with Azure tutorial

This is simple tutorial to demonstrate how to get started with provisioning Azure with Ansible. For complete more complex real-life example please check my ansible-azure repo.

## Install, setup

Follow Internet documentation to install Ansible and Azure Python SDK. Make sure you create Service Principal account in Azure (register application) and provide details either via environmental variables (example is in azurecredentials.rc.example), via ansible configuration file or any other method.

## demo01 - Playbook to deploy resource group
ansible-playbook demo01.yaml

## demo02 - Playbook to deploy resource group using variable
ansible-playbook demo02.yaml

## demo03 - Playbook to deploy resource group and virtual network
ansible-playbook demo03.yaml

## demo04 - Playbook to deploy network and VM
ansible-playbook demo03.yaml

## demo05 - Playbook to deploy network and VM, print its public IP and wait for SSH connection 
ansible-playbook demo03.yaml

## demo06 - Playbook to deploy network and VM, print its public IP and wait for SSH connection
ansible-playbook demo03.yaml

demonstrate whole process again with different resource group:

ansible-playbook demo03.yaml -e group=myanasiblegroup2






Tomas Kubica
Find me on linkedin.com/in/tkubica

