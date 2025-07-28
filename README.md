# AWS EC2 Terraform Module

This module creates AWS EC2 instances with configurable parameters.

## Usage

```hcl
module "ec2" {
  source = "github.com:mikolaj-matuszny-clearscale/tf-mod-aws-ec2.git?ref=v1.0.1"
  
  # Add your variables here
}
```

## Requirements

- Terraform >= 0.12
- AWS Provider

## Inputs

See `variables.tf` for all available input variables.

## Outputs

See `outputs.tf` for all available outputs.