# Build the docker image
docker build -t lms/node-web-app .

# Run the docker image
docker run -p 8080:8080 -d lms/node-web-app

# Access the node instance running inside docker
http://localhost:8080/