Clone or fork this repository.
Register or use existing domain in Route53 AWS Console
Edit the dev.tfvars file to specify your "domain" and your desired "bucket name"
USE IAM ROLE with right access to avoid "access and secret key" 
Run terraform init -var-file=dev.tfvars
Run terraform plan -var-file=dev.tfvars
Run terraform apply -var-file=dev.tfvars
Wait approximately 10 min for the terraform script to create your resources
Add index.html file to s3 bucket 
Go to your domain in a browser
