# Azure Resource Manager Templates for ServiceNow

This set of templates deploys the basic IaaS infrastructure necessary to deploy a ServiceNow instance to an existing Azure VNET.  This does not install ServiceNow, nor does it include a MID server or add-on servers, but those would be easy to include in the main template.

## Structure

The servicenow_infra.json template should be submitted to Azure for deployment.  This template references the vm_template.json via URL to this GitHub repository.  If for some reason you modify the vm_template, be sure to change this URL so ARM picks up your changes.

## Warranty

In short, there is none for using this template.  Please use at your own risk...  although if it makes you feel better, it deployed on the first try. ;-)