# How to Use This Setup

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
