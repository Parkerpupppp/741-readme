# 741-readme

## Step1:

Open the terminal in your VM; we use command lines to install docker.

### Write and execute the following commands to install docker:

"sudo apt update" This command refreshes the list of available packages

"sudo apt install apt-transport-https ca-certificates curl software-properties-common" install a few prerequisite packages which let apt use packages over HTTPS

"curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -" add the GPG key for the official Docker repository to your system

"sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"" Add the Docker repository to APT sources

"apt-cache policy docker-ce" install from the Docker repo

"sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin" get the latest version of docker pakages

After this, you should have the latest docker packages installed. you can use "sudo docker -v" to check the docker version.

## Step 2:

Download or write your own app.py and docker file

You can download them from http://34.28.177.100:3333/ Using user:1 password:1 to login

The necessary files are under data directory

