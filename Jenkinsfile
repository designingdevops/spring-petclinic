pipeline {
  agent {
    docker {
      image 'maven'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'mvn install'
      }
    }
  }
}