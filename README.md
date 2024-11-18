# VotingApp_K8s_minikube

 ## Prerequisites Before you start, make sure you have the following installed:
 - [Docker](https://www.docker.com/)
 - [Minikube](https://minikube.sigs.k8s.io/docs/start/)
 - [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
 
 - ## Setup Instructions
 -  ### 1. Clone the Repository Clone the repository to your local machine using: git clone
 -  ### 2. Start a minikube cluster  - minikube start
 -  ### 3. Apply the Kubernetes configurations to deploy the application:   - kubectl apply -f "name of the deployment file"
 -  ### 4. Verify the Deployment
         Check the status of the Pods to ensure they are running:
         kubectl get pods
 -  ### 5. Access the Application
        Access the application via the Minikube service:
        minikube service <service-name>

 - ### To run the application on the browser 
 -     minikube service result --url   # you will get the url after running this cmd , copy-paste in the browser and finally  your application is running  ( url:port) (http://url:30005)
 -     minikube service voting-app-service --url  (http://url:30004) 

