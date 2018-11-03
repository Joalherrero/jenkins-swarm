docker-jenkins-swarm
====================

Docker image for Jenkins, with swarm plugin installed.
Based on the [official image](https://registry.hub.docker.com/_/jenkins/).



# Running

    docker run --name jenkins -p 8080:8080 -p 50000:50000 -v /var/jenkins_home csanchez/jenkins-swarm

# Building

    docker build -t csanchez/jenkins-swarm .
