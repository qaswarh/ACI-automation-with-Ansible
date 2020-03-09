# ACI-automation-with-Ansible
Create tenant and subnets in APIC

This repository is solely created for a demo on ACI automation with Ansible

A request came to show multiple subnets creation on APIC with Ansible, though playbook has only two tasks for this demo

Requirements for this demo
--------------------------
Virtual Box at [VirtualBox.org](https://www.virtualbox.org/)

Centos ISO at [Download CentOS](https://www.centos.org/download/)

Cisco APIC Sandbox at [Cisco APIC DC](https://sandboxapicdc.cisco.com)

Ansible Modules as study items:
[aci_tenant](https://docs.ansible.com/ansible/latest/modules/aci_tenant_module.html),
[aci_vrf](https://docs.ansible.com/ansible/latest/modules/aci_vrf_module.html),
[aci_bd](https://docs.ansible.com/ansible/latest/modules/aci_bd_module.html),
[aci_bd_subnet](https://docs.ansible.com/ansible/latest/modules/aci_bd_subnet_module.html)
to modify or create Ansible domain-specific language in YAML

Procedure
---------
[Setup](https://developer.cisco.com/learning/modules/ansible-aci-intro/aci_ansible_part1/step/1) your windows computer if you don't have MAC book 

Install CentOS on Virtual Box or Hypervisor you like

[Clone](https://github.com/CiscoDevNet/aci_ansible_learning_labs_code_samples) the sample files from CiscoDevNet, modify any file either as per YAML playbook in this repository or as per your need.

Run ansible-paybook to see the same or similar results as below 

CentOS
------
![image](https://user-images.githubusercontent.com/47313728/76161863-9c5f4f00-60f4-11ea-995b-9c1fd51ebe3d.png)

APIC Sandbox
------------
![image](https://user-images.githubusercontent.com/47313728/76162004-1b08bc00-60f6-11ea-9296-3596692391e7.png)

