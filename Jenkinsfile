pipeline {
  agent {
    docker {
      image 'node:6.11.2-stretch'
    }
    
  }
  stages {
    stage('Instalacao') {
      steps {
        sh 'npm install'
      }
    }
    stage('Execucao') {
      steps {
        sh 'npm start'
      }
    }
  }
}