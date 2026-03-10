# 4640-ansible-roles-lab
Noppanat Sripan
Nuree Na
Monte Lee

## Getting started

commands we used:
```bash
ssh-keygen -t ed25519 -f ~/.ssh/aws

# install boto3
sudo apt install python3-boto3

ansible-playbook -i inventory/aws_ec2.yml playbook.yml --check

ansible-playbook -i inventory/aws_ec2.yml playbook.yml
```
