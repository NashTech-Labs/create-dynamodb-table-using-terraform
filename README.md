## Create a DynamoDB Table using Terraform.

-------------

**Files:** 
```
    main.tf
    provider.tf
    variables.tf 
```

## Apply the terraform script

1. First configure the aws credentials using aws-cli

        aws configure --profile DynamoDB

2. Now, from the current directory run the following command to validate the script.

        terraform validate

3. To check the plan for the terraform

        terraform plan

4. Applying the terraform script

        terraform apply
