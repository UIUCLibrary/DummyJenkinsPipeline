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
    stage('Create a Node') {
      steps {
        node(label: 'Windows') {
          echo 'hello from node'
          bat 'dir'
        }
        
      }
    }
  }
}