# capstone
Install terraform using following commands

$ sudo apt update
$ sudo apt install wget unzip -y
$ wget https://releases.hashicorp.com/terraform/1.0.9/terraform_1.0.9_linux_amd64.zip
$ unzip terraform_1.0.9_linux_amd64.zip
$ sudo mv terraform /usr/local/bin

install the aws cli

$ sudo apt-get install python3-pip -y
$ sudo pip3 install awscli 

use aws configure and give your credentials

create a directory and inside that directory create your terraform files to create a instance

** Make sure to modify your ami depending upon region and instance you need. Also modify the VPC id **

Once you have created instance using terraform ssh into that instance and install ansible in it

Install the ansible using the following commands

$ sudo yum check-update




