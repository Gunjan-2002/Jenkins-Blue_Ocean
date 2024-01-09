pipeline {
  agent any
  stages {
    stage('Test') {
      steps {
        sh '''
date'''
      }
    }

    stage('Build') {
      steps {
        echo 'Build Succesful'
      }
    }

    stage('Test Server') {
      steps {
        sh 'pwd'
      }
    }

    stage('Production Server') {
      steps {
        echo 'Deployed On Production Server'
      }
    }

  }
}