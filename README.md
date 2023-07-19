# Dev_CTF

This is a Developer perspective CTF where the default configuration of password management is configured. The CTF is to identify the default password configuration of MySQL Service and change as per the security best practices and submit the password in the web application to get the flag.

__Requirements__

Python 3+ and Docker


__To install__

`pip install docker-compose` or ` pip3 install docker-compose`


Download the *docker-compose.yml* file and the run the following command from the directory where the yml file is downloaded.

`docker-compose up -d`


Upon running the docker images using the yml file, access the Web Application at http://Your_IP:9450

_Note: Start your journey through Web Application._


Use `flush_docker.sh` to Stop and Remove all the containers which running.

