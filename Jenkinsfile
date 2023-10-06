pipeline {
    agent {
        any {
            image 'node:12'
            args '-p 3000:3000'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
     }
 }

