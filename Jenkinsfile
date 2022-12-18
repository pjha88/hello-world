pipeline {
  agent none {
    stages {
      stage('Checkout') {
        steps {
          sh 'echo "this is checkout stage"'
        }
      }
        stage('Build') {
        steps {
          sh 'echo "this is build stage"'
        }
      }
        stage('Deploy') {
        steps {
          sh 'echo "this is deploy stage"'
        }
      }
    }
  }
}
