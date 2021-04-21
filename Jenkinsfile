pipeline {
  agent any
  stages {
    stage('descarga') {
      steps {
        sh '''ls -lisha
'''
      }
    }

    stage('show env ') {
      steps {
        sh 'env'
      }
    }

    stage('final') {
      steps {
        git(url: 'https://github.com/kastras/jenkins', branch: 'master')
      }
    }

  }
}