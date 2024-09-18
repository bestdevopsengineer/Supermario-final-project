# integrate sonarqube into the pipeline
1) Clone SuperMario Game GitHub Repo from GitHub on local System
2) Open in Visual Studio Code
3) Add GitHub Actions to integrate SonarQube 
4) Create a Project in SonarQube
5) Create a sonar-project.properties file in your repo in Visual Studio Code and add Project Key from SonarQube
6) Create a Security Token in SonarQube
7) Create SONAR_HOST_URL and SONAR_TOKEN repository secrets in your GitHub Repo
8) Push GitHub Actions code to GitHub Repo
9) Verify that SonarQube SAST analysis runs successfully on SuperMarioGame in GitOps pipeline 


SONAR_HOST_URL: ${{ secrets.SONAR_HOST_URL }}
SONAR_TOKEN: ${{ secrets.SONAR_TOKEN }}
in sonarqube click on manually 
project name: gitopsdevsecopspipeline
github actions
generate a token


# Docker Super Mario Project Modified for Learning GitOps Pipeline by Raghu the Security Expert

## Overview
The Docker Super Mario Project is a modern adaptation of the classic Infinite Mario game, reimagined using HTML5, JavaScript, Canvas, and Audio elements. This project serves as an exemplary platform for learning and implementing GitOps pipelines, offering a hands-on approach to continuous integration and continuous deployment (CI/CD) practices.

## Features
- **HTML5 Canvas**: Delivers dynamic, scriptable rendering of 2D shapes and bitmap images.
- **JavaScript**: Ensures interactive game mechanics and responsive design.
- **Audio Elements**: Enhances the gaming experience with authentic sound effects and background music.
- **Docker Integration**: Facilitates the deployment of the application in isolated environments, making it easy to share and scale.
- **GitOps Workflow**: Introduces participants to modern DevOps practices, focusing on automation, monitoring, and version control.