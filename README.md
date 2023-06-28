# Creating_Static_Website_using_Docker_and_Nginx
# Steps
- docker --version
- docker ps -a
- docker images
- docker rm $(docker ps -aq)
- docker rmi $(docker images -q)
# Go to your folder, here is named static-website
- cd static-website
- docker build -t Azizuls-static-website .
# Open a new Browser
- http://localhost:8080/
- See your static website landed! 
# Docker is landed here!
# This Static website is hosted on Nginx with Docker
