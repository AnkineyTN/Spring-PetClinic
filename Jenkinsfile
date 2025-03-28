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
