pipeline {
  agent any
  stages {
    stage('make build') {
      steps {
        sh '''git checkout master
git pull origin master
ng build'''
      }
    }
  }
}