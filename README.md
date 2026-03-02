<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/57d29967-1c87-44b9-87df-d715683fda83" />


## Terraform Provisioner | K3S Model  🚀🚀🚀



🎯  Key Features
```
✅ Launch EC2 Instances
✅ Install K3S Binary ( Kubernetes )
✅ Prepare Cluster Configuration
✅ Deploy Helm Charts 
```

🚀 
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```

🧩 Config 

```
scp -i ~/.ssh/<your pem file> <your pem file> ec2-user@<terraform instance public ip>:/home/ec2-user
chmod 400 <your pem file>
```

