# 4640-w4-lab-start-w25

## Team members:
- Andrew Hsu
- Ash Dhatwalia

## Command to generate a new key pair:
`ssh-keygen -t rsa -f <file_path>`

## Steps to connect to the instance:
1. Go to the folder where the Terraform configuration file is stored.
2. Run the command `terraform init`.
3. Run the command `terraform apply`.
4. Type **yes** to let Terraform perform actions described in the configuration file.
5. Ssh into the instance using the dns_name or public_ip shown as the output.

## Troubleshooting guide
Issue 1: The free tier t2.micro ec2 instance is not supported in your AZ.
- Solution: Change AZ to **us-west-2a**.