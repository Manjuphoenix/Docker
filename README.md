# Docker
Steps to use this in your machine:
* create a new directory for example "myproject"
* Download the docker-compose.yum file into the directory 
* Now the code using the command "docker-compose up" and use the ip address of your machine as the url.

WORKING:
* In the docker-compose.yml file we have written the commands to pull image from the docker hub i.e, nextcloud and mysql
* The environment specifies the os for the required commands such as Root_password, user name, and user password for both the images
* The volumes section specifies the creation of new volumes (permanent storage of data) for both nextcloud and mysql
