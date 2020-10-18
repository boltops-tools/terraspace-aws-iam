# Terraspace AWS IAM Example

This project shows how to use the [AWS Identity and Access Management (IAM) Terraform module](https://registry.terraform.io/modules/terraform-aws-modules/iam/aws) with [Terraspace](https://terraspace.cloud/).

* Thanks and credit goes to the author of this module: Anton B.
* Most contributors are doing this on their own free time. Please support them. Contribute back and send them a pull request. Some may ask for donations. Donate to them. Some are consultants. Hire them.

## Setup

    git clone https://github.com/boltops-tools/terraspace-aws-iam
    cd terraspace-aws-iam
    bundle

## Deploy

To deploy:

    terraspace up iam-user

The test iam users created are `vasya.pupkin` and `vasya.pupkin4`.

## Updating

To update the modules to the latest version from the Terraform registry.

    terraspace bundle update

## More Examples

    $ terraspace list
    app/stacks/iam-account
    app/stacks/iam-assumable-role
    app/stacks/iam-assumable-role-with-oidc
    app/stacks/iam-assumable-roles
    app/stacks/iam-assumable-roles-with-saml
    app/stacks/iam-group-complete
    app/stacks/iam-group-with-assumable-roles-policy
    app/stacks/iam-group-with-policies
    app/stacks/iam-policy
    app/stacks/iam-user

## About

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

[Terraspace](https://terraspace.cloud/) and this project was built by [BoltOps](https://www.boltops.com). We also offer:

* [Paid Consulting Services](https://www.boltops.com/consulting)
* [BoltOps Pro: Infrastructure Code as a Service](https://www.boltops.com/pro)
