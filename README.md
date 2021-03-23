# Terrform with AWS
- Created VPC, Internet gateway, route table and subnet
- Associated subnet with route table
- Created security grp to allow port 22, 80, 443
- Created network interface  with an ip in subnet and assigned an elastic ip to it.
- Create an ec2 instance and installed/enabled apache in it using terraform only.

Clone the repo - 
```
git clone https://github.com/AdityaPrakash2811/terraform_intro
```

Run these commands - 
```
terraform init
terraform plan
terraform apply
```
Be sure to use your correct AWS access keys.
