# Ansible with Azure tutorial

This is simple tutorial to demonstrate how to get started with provisioning Azure with Ansible. For complete more complex real-life example please check my ansible-azure repo.

## Install, setup

Follow Internet documentation to install Ansible and Azure Python SDK. Make sure you create Service Principal account in Azure (register application) and provide details either via environmental variables (example is in azurecredentials.rc.example), via ansible configuration file or any other method.

## demo01 - ensure Azure resource group exists
ansible-playbook demo01.yaml

## demo02 - use variable
ansible-playbook demo02.yaml

## demo03 - add network and subnet resources
ansible-playbook demo03.yaml



Tomas Kubica
Find me on linkedin.com/in/tkubica

