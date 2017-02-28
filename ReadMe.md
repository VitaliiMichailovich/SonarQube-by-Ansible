Ansible instructions to install SonarQube server.
autor: Vitalii Radchenko (vitaliy.michailovich@gmail.com)

You should change ip address of your server in on bottom of inventory file.
Now it's 10.33.41.175. You should put here ip of your server.

In SonarQube.yml you should change ip address, port, username and password to your MySQL server.
And you need to create database "sonar".

To use playbook do next command "ansible-playbook SonarQube.yml -i inventory -vv".

Port is 80.
