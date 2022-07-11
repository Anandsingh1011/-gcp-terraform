# gcp-terraform
Simple solution of load-balanced nginx servers, exploring GCP and using Terraform for infra-as-code

To initialize Terraform, run the following command:

terraform init

To create an execution plan, run the following command:

terraform plan


Terraform determined that the following 4 resources need to be added:

Name	Description
mynetwork	VPC network
mynetwork-allow-http-ssh-rdp-icmp	Firewall rule to allow HTTP, SSH, RDP and ICMP
mynet-us-vm	VM instance in us-central1-a
mynet-eu-vm	VM instance in europe-west1-d


To apply the desired changes, run the following command:

terraform apply -auto-approve

