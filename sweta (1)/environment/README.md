         ___        ______     ____ _                 _  ___  
        / \ \      / / ___|   / ___| | ___  _   _  __| |/ _ \ 
       / _ \ \ /\ / /\___ \  | |   | |/ _ \| | | |/ _` | (_) |
      / ___ \ V  V /  ___) | | |___| | (_) | |_| | (_| |\__, |
     /_/   \_\_/\_/  |____/   \____|_|\___/ \__,_|\__,_|  /_/ 
 ----------------------------------------------------------------- 


Hi there! Welcome to AWS Cloud9!

To get started, create some files, play with the terminal,
or visit https://docs.aws.amazon.com/console/cloud9/ for our documentation.

Happy coding!
## Assignment 3 ACS 730

## sudo yum install -y ansible - to install ansible

## pip install boto3 for dynamic inventory in ansible

## create aws_ec2.yaml file for dynamic inventory

## key group using environment name from tags in instance details

## run ansible-inventory -i aws_ec2.yaml --graph to list out all instance and show it as graph

## create group_var folder for setting up variables for both groups

## create role folder cd inside it run ansible-galaxy init role_name

## configure files accordingly

## just because both OS has different package manage we will create two saperate roles for each OS

## after creating role we will create playbook for hosts and sign them roles to follow configurations to setup

## then run ansible-playbook -i aws_ec2.yaml playbook.yaml

## to test it launch one instance with debian or amazone ami and give it a tag environment debian or linux and run the command and check public_ip static website will be setup there. 