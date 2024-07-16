"# terraform_ec2_s3" 

git clone git@github.com:adylimmo/terraform_ec2_s3.git
cp terraform.tfvars.example terraform.tfvars
change access_key, secret_key and region
terraform plan
terraform apply -auto-approve
