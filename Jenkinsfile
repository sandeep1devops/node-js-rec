pipeline {
    agent {
        any {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
     environment {            
        PATH = "/usr/bin/npm:/share/nodejs/npm/bin:${env.PATH}"
    }
        
    stages {
        stage('Build') {
            steps {
                sh '/usr/bin/npm install'
//              sh 'npm install'
           }
        }
     }
 }
