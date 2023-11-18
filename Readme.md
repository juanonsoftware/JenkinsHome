## To start jenkins by running below command:

docker run -itd --rm -p 8080:8080 -p 50000:50000 -v D:\Dev\Docker\Jenkins\jenkins_home:/var/jenkins_home --name jenkins-latest-jdk21 jenkins/jenkins:latest-jdk21

## To stop (and auto remove) jenkins:

docker stop jenkins-latest-jdk21