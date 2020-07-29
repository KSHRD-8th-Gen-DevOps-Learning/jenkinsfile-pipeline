pipeline {
  agent any
  stages {
    stage("build") {
      steps {
        echo "====++++Build the Application++++===="
      }
    }
    stage("test") {
      steps {
        echo "====++++Test the Application++++===="
      }
    }
    stage("deploy") {
      stage {
        echo "====++++Deploy the Application++++===="
      }
    }
  }
}