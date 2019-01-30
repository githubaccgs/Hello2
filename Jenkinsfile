
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
        //./testscript.sh
        sh('https://github.com/githubaccgs/Hello2/blob/master/testscript.sh')
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
