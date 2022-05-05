# Terraform on Azure with Azure IaC DevOps for Terraform Project

```
1. Implement IaC usecases with Terraform on Azure cloud using Azure DevOps
2. Implement Azure Build Pipelines (Continuous Integration Pipelines)
3. Implement Azure Release Pipelines (Continuous Delivery Pipelines)

..............................................................................

4. dev.tfvars, qa.tfvars, stage.tfvars and prod.tfvars files are used to provision different environments
5. For the terraform backend to store state of each enviroment azure storage is used.

```
### Continuous Integration CI azure pipeline for build artifacts

![Screenshot (3406)](https://user-images.githubusercontent.com/21228768/166950208-4a8de497-ad59-44c3-896c-e6f01e8f13e7.png)

### Continuous Deployment CD pipeline getting artifacts and deploying on Dev, QA, Stage and Prod Environments

![Screenshot (3407)](https://user-images.githubusercontent.com/21228768/166950311-0b0ae23b-70d0-4163-8fd9-0833348e338c.png)
