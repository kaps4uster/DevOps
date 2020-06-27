pipeline {
  agent any
  stages {
    stage('Compile') {
      steps{
        sh 'mvn clean compile '
      }
    }
   
 stage('Unit kapil Test') {
      steps{
        sh 'mvn clean test'
      }
    }
 
   
  }
}
