## Terraform AWS Example

This project is an example of Infrastructure As Code using Terraform with AWS cloud provider.

---
## Setup Environment

Create a SSH key:

    ssh-keygen

Set the path to the key generated in terraform.tfvars:

    public_key_path = "/put/your/path/here/key.pub"


## How to run

Initialize the environment:

    terraform init

Validate the code:

    terraform validate

Plan the changes:

    terraform plan

Apply changes:

    terraform apply -auto-approve

Destroy environment:

    terraform destroy -auto-approve