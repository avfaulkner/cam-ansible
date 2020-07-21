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
2. Modify the hosts file consisting of the public IPs and host variables of the target hosts.  
3. Modify the ssh.cfg file that designates the username, port and ssh connection information for the bastion.


**Note**

In order to use CAM Standalone software, a registration code
must be obtained from [Teradici](https://www.teradici.com/)
