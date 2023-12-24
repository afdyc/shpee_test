1. Lets say we have an application, messageQueue, and a database, then we want to make each of them portable,
   so we containerized each component using lets say docker. Now lets say we have a Virtual Machine and on top of it we run kubernetes to orchestrate these containers using kubernetes cluster.
   and each component that we have will be deployed as a kubernetes pod. Now we define Deployments to manage the desired state of our Pods.
   Deployments ensure a specified number of replicas (instances) of each component are running. If a Pod fails, the Deployment automatically replaces it.

2. We might need kubernetes when we have lets say a lot of traffic, thats when we need to scale up our environtment.
   and to scale up our environtment that might be costly and time consuming, when we use kubernetes we can automate deployment and scaling
