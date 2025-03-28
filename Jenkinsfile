pipeline {
  agent any
  stages {
    stage("checkout") {
      steps {
        echo "Pulling scm"
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
