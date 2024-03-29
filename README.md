# AWS-SES

<!-- retro visitor counter -->
<p align="center"> 
<img src="https://profile-counter.glitch.me/ValAug/count.svg" />
</p>

This repository create an __AWS:__

 - __SES domain verification with R53__

# AWS SES diagram 
![ses-r53](https://github.com/ValAug/AWS-SES/blob/main/ses-2.png)
###### Cloud - :cloud:
![AWS](https://img.shields.io/badge/-AWS-000000?style=flat&logo=Amazon%20AWS&logoColor=FF9900)

###### IaaC
![Terraform](https://img.shields.io/badge/-Terraform-000000?style=flat&logo=Terraform)

# Prerequisites

* You must have an AWS account, and have your CLI profile configuration.

* You must have Terraform installed
    - [how to install terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli)

# Cautions

* As an AWS best practice, grant this code least privilege, or only the 
  permissions required to perform a task. For more information, see 
  [Grant Least Privilege](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege) 
  in the *AWS Identity and Access Management 
  User Guide*.
* This code has been tested in __us-east-1__ AWS Regions only. However it should work in any other region. 
* Running this code __it might__ result in charges to your AWS account.

# How to run this code

- [How to run this code](#how-to-run-this-code)
  - [Quick Start](#quick-start)
  - [Quick Destroy](#quick-destroy)
  - [Steps to follow](#Steps-to-follow)

## Quick Start

```bash
cd vpc-endpoint-connection-with-s3
terraform init
terraform validate
terraform plan
terraform apply --auto-approve
```
## Quick Destroy

```bash
terraform destroy --auto-approve
```

## Steps to follow

- clone this GitHub repository
- cd to the the directory __SES domain verification with R53__

- __Terraform-commands:__
    - __terraform --help__
    - __terraform init__ Prepare your working directory for other commands
    - __terraform validate__ Check whether the configuration is valid
    - __terraform plan__ Show changes required by the current configuration
    - __terraform apply__  Create or update infrastructure
    - __Alternate command:__ terraform apply -auto-approve
    - __terraform destroy__ Destroy previously-created infrastructure
    - __Alternate command:__ terraform destroy -auto-approve
    - __terraform fmt -recursive__ Reformat your configuration in the standard style
