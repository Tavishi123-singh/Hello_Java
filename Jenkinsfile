pipeline{
  agent any
  stages{
    stage('Build'){
      steps{
        sh 'javac Hello.java'
        sh 'java Hello'
      }
    }
  }
}
