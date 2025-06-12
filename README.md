* Terraform code
  
* * Maintain vpc & eks with terraform for vprofile project
** Tools required
Terraform varsion 1.6.3

***steps
*  terraform init
*  terraform fmt -check
*  terraform validate
*  terraform plan -out planfile
*  terraform apply -auto-approve -input=false -parallelism=1 planfile
