# Terraform-Azure-advanced
Setup ssh key in main.tf using tls_key

Get pem key-> terraform output -raw tls_private_key > id_rsa
Login with key-> ssh -i id_rsa azureuser@<public_ip_address>

