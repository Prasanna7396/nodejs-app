# NodeJsApp
This is a simple maven nodejs application.
The application is dockerized and deployed on aws eks cluster using terraform.
The docker image is pushed onto AWS ECR and Terraform scripts to AWS S3 bucket.
The application is exposed using loadbalancer on port 8050.
