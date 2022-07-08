pipeline{
  agent any
  
  stages{
    stage("build"){
      steps{
        echo 'building the app'
        sh 'javac abc.java'
      }
    }
    stage("test"){
      steps{
        echo 'testing the app'
        sh 'java abc'
      }
    }
    stage("deploy"){
      steps{
        echo 'deploying the app'
      }
    }
  }
}
