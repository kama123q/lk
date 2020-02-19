pipeline {
  agent any
  stages {
    stage('test') {
      agent {
        node {
          label 'master'
        }

      }
      steps {
        sh 'echo "Testing bserver"'
      }
    }

    stage('develop') {
      steps {
        sh 'echo "Develop server"'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "Deploye"'
      }
    }

  }
}