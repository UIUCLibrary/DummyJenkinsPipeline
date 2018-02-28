pipeline {
  agent any
  stages {
    stage('Say Hi') {
      steps {
        echo 'Hello World'
        node("Windows") {
          echo "inside a node"
          bat "dir"
        }
      }
    }
  }
}
