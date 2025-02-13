# How to Use This Setup

In version 4.0 of the Azure Provider, it's required to specify the Azure Subscription ID when configuring a provider instance in your configuration. Set your own subscription ID.

### Initialize Terraform

```
terraform init
```


### Plan the Deployment

```
terraform plan -var-file="variables.tfvars"
```


### Apply the Deployment

```
terraform apply -var-file="variables.tfvars" -auto-approve
```


### Check Outputs

```
terraform output
```
