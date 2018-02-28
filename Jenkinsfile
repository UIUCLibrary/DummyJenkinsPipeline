pipeline {
  agent {
    node {
      label 'Windows'
    }
    
  }
  stages {
    stage('Say Hi') {
      steps {
        echo 'Hello World'
      }
    }
    stage('try docker') {
      steps {
        echo "Trying docker"
      }
    }
  }
}
