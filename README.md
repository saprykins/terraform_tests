# terraform_tests

Get project_id
```
gcloud config list project
```
Replace the "<PROJECT_ID>" by project_id  
  
Create main.tf file  
  
Copy content from github main.tf file  

Initialize local settings where main.tf file is located    
```
terraform init
```
Apply configurqtions by  
```
terraform apply
```

Type "yes"

To check what was created:  
```
terraform show
```
Destroy created infrastructure by  
```
terraform destroy
```

More details on explicit and implicit dependencies are  

[here](https://partner.cloudskillsboost.google/focuses/16374?catalog_rank=%7B%22rank%22%3A4%2C%22num_filters%22%3A1%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=17479657)

The link works only for partners
