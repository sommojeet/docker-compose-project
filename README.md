# docker-compose-project

Here are the steps I followed to create this project:-

1) Installed docker using command ```yum install docker-ce --nobest```.
2) Disabled firewall, because it create conflicts while connecting to web server. Command is ```systemctl stop firewalld```.
To keep it disabled even after reboot, ```systemctl disable firewalld```.
3) Started docker services using command ```systemctl start docker```, enabled permanently using ```systemctl enable docker```
4) Downloaded wordpress and my sql images from docker hub using comands

```docker pull wordpress:5.1.1-php7.3-apache```

```docker pull mysql:5.7```

5) Created a workspace for docker compose naming "mycompose"
6) inside workspace created the file ```docker-compose.yml``` and wrote the code in yaml format. The entire code is available in this repository with the exact same name. You can download this repo in your redhat system by following the below steps.

Download this repo by copying the link provded in the "Clone or download" button in green at the right.
then, use the command in your terminal:

```git clone copied_link -b master your_desired_directory```

for example:

```git clone https://github.com/sommojeet/docker-compose-project.git -b master root/mycompose```

Now go to the directory where you downloaded and do:

```docker-compose up```

This will start both the services of wordpress and database.

