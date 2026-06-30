# i2i-Academy-Containerization-2

In this project, I used Docker and Docker Compose to deploy a simple static web page.

Here, I created an index.html file and a docker-compose.yml file with the help of nginx image. First, I ran the container on my local machine using port 3000 and then tested it from the browser. In case of Cloud VM deployment, I used port 80, since, GCP’s firewall allows HTTP traffic only to this port and I did not want to create any additional firewall rules.
