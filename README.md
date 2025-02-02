# 4640-w4-lab-start-w25


See lab instructions on D2L for details


Instructions on General Setup:
1. Install Terraform and  setup Git
2. Clone the starter files
3. Create a new Key Pair
4. Edit the cloud-config.yaml and main.tf files
5. Run Terraform apply
6. Connect to the instance by running ssh -i terraform_lab_key web@<ip-address>

Command used to create a new SSH key pair:
1. ssh-keygen -t rsa -b 4096 -C "rhernandez35@my.bcit.ca" -f ~/.ssh/terraform_lab_key

Commands used to initialize, fmt, plan... configuration:
1. terraform init
2. terraform fmt
3. terraform plan
4. terraform apply
5. Connect to the instance by running ssh -i terraform_lab_key web@<ip-address>

