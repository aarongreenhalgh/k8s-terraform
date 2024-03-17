# k8s-terraform
Let's deploy a simple web app to a AKS using Terraform

docker build -t web-app-example ./
docker run -p 8080:80 web-app-example