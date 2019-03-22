Jenkinsfile (Declarative Pipeline)
pipeline {
  tools {
    Docker 'ubuntu:16.04'

  }
    agent { docker { image 'python:3.5.1' } }
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}
