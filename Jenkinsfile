pipeline {
    agent {
        label 'agent2'
    }
    stages {
        stage('Build') { 
            steps {
                sh 'npm install' 
            }
        }
    }
    stage('Test') { 
        steps {
            sh './jenkins/scripts/test.sh' 
        }
    }
}