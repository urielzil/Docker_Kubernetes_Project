by URIEL ZILBERBERG

Docker Image Creation: 
Created a Docker image using the iperf server and uploaded it to Docker Hub.

VM Interaction:
Wrote a bash script that deployed the Docker container on one virtual machine (VM) while running an iperf client on another VM to send packets to the container.

Kubernetes Setup: 
Installed Kubernetes with Docker as the container runtime and Weave Net as the network plugin.

Custom Nginx Image: 
Created a custom nginx Docker image that returned specific information and uploaded two versions of the image to Docker Hub.

Kubernetes Resources:
Created Kubernetes resources, including Deployment, Service, and HorizontalPodAutoscaler, using YAML files. 
Wrote a bash script to automate operations on the deployed application.
