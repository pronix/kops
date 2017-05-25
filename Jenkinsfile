pipeline {
  agent {
    docker {
      image 'centos7'
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