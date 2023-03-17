# blog-microservices

This is simple blog application, which was built using microservices architecture. 
I have custom built Event Bus to communicate between the services.
Each of these services are inside the Docker container and Kubernetes is used to orchastrate the containers.
Kubenretes Load Balancer service in combination with Ingress is used to manage communication between pods.
Skaffold is used for development and to get live updates of the code ASAP.
Nginx is used to serve client app that was built using React.
