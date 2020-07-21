# cam-ansible

***Currently WIP***

Configures CAM Standalone software. 

## Requirements
### Tooling
- Ansible >= 2.9.10

# Directions for usage
This is currently being run as a playbook from a local workstation. 

## Steps 
1. Clone the repo onto the local workstation and run the role as part of a playbook.
2. Create an inventory file consisting of the public IPs of the target hosts.  
3. Create an ssh config file that designates the username, port and ssh connection information for the bastion.


**Note**

In order to use CAM Standalone software, a registration code
must be obtained from [Teradici](https://www.teradici.com/)
