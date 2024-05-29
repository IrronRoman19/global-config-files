pipeline {
    agent any
    stages {
        stage('Start') {
            steps {
                sh 'echo Starting proccess'
                sh 'echo my first jenkinsfile'
            }
        }
        stage('CheckNodeVer') { 
            steps {
                sh 'echo Checking the node version'
                sh '/usr/local/bin/node -v'
            }
        }
        stage('Build') { 
            steps {
                sh 'echo Building application'
                sh 'node /usr/local/bin/app.js'
            }
        }
    }
}