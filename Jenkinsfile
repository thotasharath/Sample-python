pipeline{
  agent any
  stages{
    stage('Execute python'){
      steps{
        sh 'pip install queuelib'
        sh 'python Game.py'
      }
    }
  }
}

