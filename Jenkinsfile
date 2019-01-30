
pipeline {
  agent any
  tools {
    gradle 'Default'
    //ant 'Default'   // this works fine but our jenkins should have an installation with name default.
  }
  stages {
    stage("Build") {
      steps {
        echo "building..."
        echo "inside Build stage...."
        ./testscript.sh
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
