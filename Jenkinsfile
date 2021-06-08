pipeline {
  
  agent any
  
  stages {
    steps {
    withGradle()
      {
      sh'./gradlew -v'
      }
    }
    stage("Build") {
      steps {
        echo 'Building ......'
      }
    }
    
    stage("Test") {
    steps
      {
        echo'Testing......'
      }
    }
    
    stage("Deploy") {
      steps  {
        echo'Deploying ......'
      }
    }
  }

}
