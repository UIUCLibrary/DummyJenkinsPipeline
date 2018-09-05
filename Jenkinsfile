pipeline {
  agent {
    node {
      label 'Windows'
    } 
  }
  tools {
      git 'Default'
      cmake 'cmake3.12'
  }
  stages {
    
    stage('Say Hi') {
      steps {
        echo 'Hello World'
        bat "where cmake"
      }
    }
  }
}
