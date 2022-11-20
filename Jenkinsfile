pipeline {
  agent {
    node {
      label 'hh'
    }

  }
  stages {
    stage('df') {
      parallel {
        stage('df') {
          steps {
            timestamps() {
              sh 'ls'
            }

          }
        }

        stage('test') {
          steps {
            git(url: 'https://github.com/riyangit/jenkins/tree/main', branch: 'd')
          }
        }

      }
    }

  }
  environment {
    hh = '66'
  }
}