# Guestbook Application

Guestbook is a simple web application built and deployed using Docker and Kubernetes. 
It consists of a web front end allowing users to enter text and submit. 

## Learning and Achievements

Through this project, I achieved the following:

- Gained hands-on experience in building and deploying web applications using Docker and Kubernetes.
- Learned to create and manage Kubernetes deployments and pods.
- Implemented Horizontal Pod Autoscaling for efficient resource utilization.
- Mastered the process of performing rolling updates and rollbacks seamlessly.
- Honed skills in Docker image building and pushing images to container registries.
- Acquired proficiency in accessing applications via port-forwarding.
- Developed a comprehensive understanding of cloud-native application development and deployment practices.
- Equipped with the knowledge and skills necessary for future projects in cloud computing and DevOps.


## Key steps completed:

## 1. Build and Deploy the Guestbook App

- Built the guestbook app using Docker Build command.
- Pushed the image to IBM Cloud Container Registry.
- Applied the deployment using `kubectl apply -f deployment.yml`.
- Launched the application on port 3000.

## 2. Autoscale the Guestbook Application

- Autoscaled the Guestbook deployment using Horizontal Pod Autoscaler.
- Observed autoscaling by generating load on the app.
- Checked the status of HorizontalPodAutoscaler.

## 3. Perform Rolling Updates and Rollbacks

- Updated title and header in index.html.
- Built and pushed the updated app image.
- Updated CPU values in deployment.yml.
- Checked deployment rollout history.
- Observed details of deployment rollout revisions.
- Observed replica sets and performed rollback.

*Note: Screenshots of Autoscaler details saved as hpa2.png.*
![up-app](https://github.com/cagri32/Kubernetes-Guestbook-App/assets/43071105/28a87c68-ab6e-4684-92c2-8c4c6b42b7dc)
