# Jenkins

## What is Jenkins?
> Jenkins is a free and open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery

## Installation on ubuntu 20.04

> Step-1:\
> `wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -`

> Step-2:\
> `sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'`\
> `sudo apt update`

> Step-3:\
> `sudo apt install jenkins`

> Step-4:\
> `sudo systemctl start jenkins`

> `sudo ufw allow 8080`

> `sudo ufw status`
