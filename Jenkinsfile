pipeline{
  agent any
  stages{
    stage('Execute python'){
      steps{
        sh 'pip install queuelib'
        sh 'python3 Game.py'
      }
    }
  }
}

