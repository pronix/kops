pipeline {
  agent {
    docker {
      image 'cento7'
    }
    
  }
  stages {
    stage('install make') {
      steps {
        sh 'yum install make -y '
      }
    }
    stage('make ci') {
      steps {
        sh 'make ci'
      }
    }
  }
}