pipeline{
  agent any
  options {
        timeout(time: 30, unit: 'SECONDS')
  }
  stages{
    stage('Build'){
      steps{
        bat 'javac Hello.java'
        bat 'java Hello'
      }
    }
  }
}
