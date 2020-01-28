Automating the Deployment of Infrastructure Using Deployment Manager

Objectives:
- Create a configuration for an auto mode network
- Create a configuration for a firewall rule
- Create a template for VM instances
- Create and deploy a configuration
- Verify the deployment of a configuration

To deploy the configuration:

#Create deployment and preview resources before their creation
>gcloud deployment-manager deployments create demoinfra --config=config.yaml --preview

#Create actual resources
>gcloud deployment-manager deployments update demoinfra

#Delete deployment if needed
>gcloud deployment-manager deployments delete demoinfra


Taken from QuikLabs: https://googlepluralsight.qwiklabs.com/focuses/37343