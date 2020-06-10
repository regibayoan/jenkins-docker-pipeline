# jenkins-docker-pipeline

Uses Jenkinsfile to automate CI/CD pipeline

1. Ubuntu EC2 instance
2. Installed Docker
3. Run Jenkins as a Docker container
4. Connect Jenkins to Github repo with PollSCM
5. Jenkinsfile clones an application from a Github project, finds the Dockerfile and builds a Docker image
6. Pushes Docker image to Docker Hub
