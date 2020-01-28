Automating the Deployment of Infrastructure Using Terraform

Objectives:

- Create a configuration for an auto mode network
- Create a configuration for a firewall rule
- Create a module for VM instances
- Create and deploy a configuration
- Verify the deployment of a configuration

To deploy the configuration:

>cd tf-demoinfra

#Init terraform with given providers
>terraform init

#To rewrite the Terraform configuration files to a canonical format and style, run the following command:
>terraform fmt

#To initialize Terraform with modules, run the following command:
>terraform init

#To create an execution plan, run the following command
>terraform plan

#To apply the desired changes, run the following command:
>terraform apply




Taken from QwikLabs: https://googlepluralsight.qwiklabs.com/focuses/37345

Terraform Module Registry: https://registry.terraform.io/browse/modules?provider=google&verified=true
