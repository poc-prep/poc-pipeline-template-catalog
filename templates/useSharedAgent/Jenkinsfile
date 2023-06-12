pipeline {
  agent none
  stages {
    stage('Build') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Build Stage'
      }
    }
    stage('Dev') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Dev Stage'
      }
    }
    stage('Test') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Test Stage'
      }
    }
    stage('Prod') {
      agent {
        node {
          label 'default'
        }

      }
      steps {
        echo 'Prod Stage'
      }
    }
  }
}
