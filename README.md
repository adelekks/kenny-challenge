# kenny-challenge
# SED Challenge

This Terraform Module will Create and deploy a running instance of a web server with Elastic Load Balancer
Create new VPC resources (VPC, subnet, security group and ELB) as well as EC2 instance.

## Usage

To run this example you need to execute:

```bash
$ terraform init
$ terraform plan
$ terraform apply
```

Note that this example may create resources which cost money. Run `terraform destroy` when you don't need these resources.

## Requirements

apache self signed certificate and import to AWS

## Providers

| Name | Version |
|------|---------|
| aws | n/a |

## Inputs

No input.

## Outputs

| Name | Description |
|------|-------------|
| this\_elb\_dns\_name | DNS Name of the ELB |

