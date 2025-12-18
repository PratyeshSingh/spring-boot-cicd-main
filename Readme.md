
# Jenkins commands:
- Install the latest LTS version: brew install jenkins-lts
- Start the Jenkins service: brew services start jenkins-lts
- Stop the Jenkins service: brew services stop jenkins-lts
- Restart the Jenkins service: brew services restart jenkins-lts
- Update the Jenkins version: brew upgrade jenkins-lts

### Common Error in Jenkins
- [Pipeline] sh docker build -t pratyesh3/spring-boot-docker .
  /Users/pratyesh/.jenkins/workspace/pipeline_test@tmp/durable-4ee1688d/script.sh.copy: line 1: docker: command not found

### Admin Password Location

- 469f5c16d0ef482ba697e6f2c592a154
- Location ( /Users/pratyesh/.jenkins/secrets/.jenkins/secrets/initialAdminPassword )

### Jenkin configuration
![Screenshot 2025-12-18 at 11.13.54 AM.png](jenkins_screenshots/Screenshot%202025-12-18%20at%2011.13.54%E2%80%AFAM.png) {width=200}
![Screenshot 2025-12-18 at 11.18.50 AM.png](jenkins_screenshots/Screenshot%202025-12-18%20at%2011.18.50%E2%80%AFAM.png) {width=200}


### Jenkins URL
http://localhost:8080/

- user := pratyesh
- pwd := admin
- Run Project function := http://localhost:8080/welcome

# Downloads
- https://www.jenkins.io/download/lts/macos/
- https://www.macminivault.com/installing-jenkins-on-macos/
- https://www.jenkins.io/doc/book/installing/macos/
- https://www.jetbrains.com.cn/en-us/products/compare/?product=idea-ce&amp;product=idea


# Docker
- https://www.docker.com/products/docker-desktop/


# Database Tool PGAdmin
- https://www.pgadmin.org/download/pgadmin-4-macos/
- install arm64.dmg (for apple Silicon chip)