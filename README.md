1. Clone or fork this repository.

2. Register or use existing domain in Route53 AWS Console

3. Edit the dev.tfvars file to specify your "domain" and your desired "bucket name"

4. USE IAM ROLE with right access to avoid "access and secret key" 

5. Run terraform init -var-file=dev.tfvars

6. Run terraform plan -var-file=dev.tfvars

7. Run terraform apply -var-file=dev.tfvars

8. Wait approximately 10 min for the terraform script to create your resources

9. Add index.html and error.html file to s3 bucket 

10. Go to your domain in a browser
