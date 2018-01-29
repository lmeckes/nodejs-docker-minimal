# Build the docker image
docker build -t lms/node-web-app .

# Run the docker image
docker run -p 3333:8080 -d lms/node-web-app