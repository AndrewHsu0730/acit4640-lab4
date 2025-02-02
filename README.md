# 4640-w4-lab-start-w25

## Team members:
- Andrew Hsu
- Ash Dhatwalia

## Command to generate a new key pair:
`ssh-keygen -t rsa -f "/mnt/c/Users/Andrew Hsu/.ssh/acit4640-lab4-key"`

## Steps to connect to the instance:
1. Go to the folder where the Terraform configuration file is stored.
2. Run the command `terraform init`.
3. Run the command `terraform apply`.
4. Type **yes** to let Terraform perform actions described in the configuration file.
5. Ssh into the instance using the dns_name or public_ip shown as the output.