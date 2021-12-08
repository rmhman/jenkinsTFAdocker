# jenkins-docker
docker build -t jenkins:2.324 -t jenkins:latest .
docker run --name jenkinsagent01 -p 2222:22 -d jenkins 
