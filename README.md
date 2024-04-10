
# Creating a Sytemd service in RHEL server with Ansible.

- we are creating a ansible project to create a systemd service on a RHEL server in a location /usr/local/lib/systemd/system/

## Pre-requisites for the service creation.

- Environment File if Virtual environment set for application.
- source files to setup the application Environment if any..
- Execution start script for the application (manadatory)
- specified Application user with enough Sudo right.

# Official documentation of the systemd service

Please go through the systemd once before starting 
[Managing Services with systemd](access.redhat.com/documentation/en-us/red_hat_enterprise_linux/7/html/system_administrators_guide/chap-managing_services_with_systemd)


# Steps to create a projects in Ansible AWX.

1. Open AWX web interface and login with user with role System Administator(admin)
2. Go to Project section and click on Add button to add new project.
   
![Project Creation in AWX](https://github.com/mtptisid/Systemd-related/blob/master/Screenshot%202024-04-10%20171031.png)

3. In create new Project page Specify your Project Name and Descriptions with SCM selctions and URL.

![Creating new Project]()
