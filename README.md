### Network Security Projects For Phising Data

<img width="1288" height="679" alt="image" src="https://github.com/user-attachments/assets/2481e365-1b19-4dcd-86fb-2bbc68d31fd1" />


Setup github secrets:
AWS_ACCESS_KEY_ID=<Enter Your Access Key>

AWS_SECRET_ACCESS_KEY=<Enter Your Secret key>

AWS_REGION = us-east-1

AWS_ECR_LOGIN_URI = 
ECR_REPOSITORY_NAME = 


Docker Setup In EC2 commands to be Executed
#optinal

sudo apt-get update -y

sudo apt-get upgrade

#required

curl -fsSL https://get.docker.com -o get-docker.sh

sudo sh get-docker.sh

sudo usermod -aG docker ubuntu

newgrp docker
