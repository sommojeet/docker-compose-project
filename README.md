# docker-compose-project

Download this repo by copying the link provded in the "Clone or download" button in green at the right.
then, use the command in your terminal:

```git clone copied_link -b master your_desired_directory```

for example:

```git clone https://github.com/sommojeet/docker-compose-project.git -b master root/mycompose```

Now go to the directory where you downloaded and do:

```docker-compose up```

This will start both the services of wordpress and database and now you're ready to access my web page.
To access:
1. Note down your IP by using the command ```ifconfig enp0s3```
2. Now put IP in front of the link:
            ```http://your_IP:8081/2020/04/26/motivation-what-is-it/```
3. You should be able to see my web page now.
