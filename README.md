***Spring + Docker Helloworld***

**BUILD**
1. install docker
2. `docker login`
3. `gradlew clean buildDocker`

**LAUNCH**

`docker run -d -p 8080:8080 ${repo_name}/hello_app:0.0.1-snapshot`