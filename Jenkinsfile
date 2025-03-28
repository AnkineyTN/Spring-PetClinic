pipeline {
  agent any
  stages {
    stage("checkout") {
      steps {
        checkout scm
      }
    }
    stage("building") {
      steps {
        echo $HOME
        echo "Building project"
      }
    }
    stage("Test") {
      steps {
        echo "Testing project"
      }
    }
  }
}
