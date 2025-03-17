pipeline {
    agent {
        label 'Agent-1'
    }
    options {
        timeout(time: 1, unit: 'SECONDS')
    }
    stages {
        stage('Build')
        {
            steps 
            {
          sh 'echo This is Building stage'
            }
        }
         stage('Scan') 
         {
            steps 
            {
              sh 'echo This is scanning stage'
            }
         }
          stage('Test') {
            steps {
               sh 'echo This is testing stage'
                sh 'sleep 10'
            }
          }
    }
}