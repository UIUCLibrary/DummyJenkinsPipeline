pipeline {
  agent {
    node {
      label 'Windows'
    }
    
  }
  stages {
    tools {
      git 'Default'
    }
    stage('Say Hi') {
      steps {
        echo 'Hello World'
      }
    }
  }
}
