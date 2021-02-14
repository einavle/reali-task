For the sake of this task, I created a cluster and deployed an argoCD application in it.

Inside the argoCD, I created our sample application.
Please see detailes below

# This project has two folders

## pipeline
- build the provided application (https://github.com/reali-devops/python-app)
- push it to a docker hub (einavl)
- sync the helm application (integrate with the argoCD application that deployed on our cluster)

## reali
 - define the k8s application that runs the provided sample above
 
 
 ## Pipline image
 
  ![Screenshot](images/reali-codefresh.png)
 
## ArgoCD App
a visualization of our sample app deployment layout
 ![Screenshot](images/reali-argoCD.png)
