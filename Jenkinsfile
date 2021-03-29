pipeline{
  agent any
  
  stages{
    timeout(time: 30, unit: 'SECONDS') {
    stage('Build'){
      steps{
        bat 'javac Hello.java'
        bat 'java Hello'
      }
    }
  }
    
  }
}
