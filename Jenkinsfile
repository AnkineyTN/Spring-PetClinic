pipeline {
  agent any
  stages {
    stage("checkout") {
      steps {
        checkout scm
        sh '''
          echo "Checkout SCM Successfully"
        '''
      }
    }
    stage("building") {
      steps {
        echo $HOME
        echo "Building project"
        sh '''
          echo "Build project Successfully"
        '''
      }
    }
    stage("Test") {
      steps {
        echo "Testing project"
        sh '''
          echo "Test Successfully"
        '''
      }
    }
  }
}
