"# terraform_ec2_s3" 

```
git clone git@github.com:adylimmo/terraform_ec2_s3.git
cd terraform_ec2_s3
cp terraform.tfvars.example terraform.tfvars
```

change access_key, secret_key and region


```
terraform init
terraform plan
terraform apply -auto-approve
terraform output
```

public_dns = "ec2-13-213-9-114.ap-southeast-1.compute.amazonaws.com"
public_ip = "13.213.9.114"

Akses  EC2


```
ssh -i keypair_anakdevops.pem ubuntu@ec2-13-213-9-114.ap-southeast-1.compute.amazonaws.com
```

Are you sure you want to continue connecting (yes/no/[fingerprint])? yes


view mount S3 on mnt/s3-bucket

```
sudo su
df -h
```

Delete all

```
terraform destroy -auto-approve
```