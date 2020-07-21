# cam-ansible

***Currently WIP***

Configures CAM Standalone software. 

## Requirements
### Tooling
- Ansible >= 2.9.10

# Directions for usage
This is currently being run as a playbook from a local workstation. 

## Steps 
1. Clone the repo onto the local workstation to run the playbook locally.
2. Modify the hosts file consisting of the public IPs and host variables of the target hosts.  
3. Modify the ssh.cfg file that designates the username, port and ssh connection information for the target host.
4. Modify the group_vars/vars.yml file with the proper variables.
5. After running the script, the output of the [configure-cam : Run the installer] section will contain the temporary password
and username to log in to the CAM Standalone web interface. 

```
...
Standalone installation complete *****\"", 
"time=\"2020-07-21T22:39:42Z\" level=info 
msg=\"The IP address of your CAM\" ip=10.0.10.66", 
"time=\"2020-07-21T22:39:42Z\" level=info msg=\"Please use the following username and password to login to CAM for the first time\"", 
"time=\"2020-07-21T22:39:42Z\" level=info Password=lN9uRvHtMPwEedwf Username=camAdmin", 
...
```


**Note**

In order to use CAM Standalone software, a registration code
must be obtained from [Teradici](https://www.teradici.com/)
