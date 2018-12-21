# Personal Jenkins Docker image

The Jenkins Continuous Integration and Delivery server [available on Docker Hub](https://cloud.docker.com/repository/docker/ptorrezao/jenkins-master).

This is a fully functional Jenkins server.
[https://jenkins.io/](https://jenkins.io/).

<img src="https://jenkins.io/sites/default/files/jenkins_logo.png"/>

# Usage

```
docker-compose -f docker-compose.yml up
```

Default Ports: 

    - '8080:8080'
    - '50000:50000'

Default User/Pwd:

    - admin/admin