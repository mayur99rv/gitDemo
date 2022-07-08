pipeline{
  agent any
  
  stages{
    stage("build"){
      steps{
        echo 'building the app'
        bat 'javac abc.java'
      }
    }
    stage("test"){
      steps{
        echo 'testing the app'
        bat 'java abc'
      }
    }
    stage("deploy"){
      steps{
        echo 'deploying the app'
      }
    }
  }
}
