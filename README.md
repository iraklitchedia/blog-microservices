# blog-microservices

This is simple blog application, which was built using microservices architecture. <br /> 
Custom built Event Bus is used to communicate between the services. <br /> 
Each of these services are inside the Docker container and Kubernetes is used to orchastrate the containers. <br /> 
Kubenretes Load Balancer service in combination with Ingress is used to manage communication between pods and client app. <br /> 
Skaffold is used for development and to get live updates of the code ASAP.<br /> 
Nginx is used to serve client app that was built using React. <br /> 
