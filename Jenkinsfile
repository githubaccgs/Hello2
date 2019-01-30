
pipeline {
  agent any
  tools {
    gradle 'Default'
  }
  stages {
    stage("Build") {
      steps {
        echo "building..."
        echo "inside Build stage...."
      }
    }
    stage("Test") {
      steps {
        echo "testing..."
      }
    }
    stage("Package") {
      steps {
        echo "packaging..."
      }
    }
  }
}
