# Sample Kubernetes application

1. Builder docker container: docker build -t {docker_account_name}/{service_name} .
   Eg: docker build -t harikrishnankr/posts .
2. Create Deployments/Service/Load Balancer: kubectl apply -f {deployment_file}.yaml
   Eg: kubectl apply -f posts-depl.yaml
3. Skaffold for hot reloading: skaffold dev 
