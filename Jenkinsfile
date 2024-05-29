pipeline {
    agent any
    stages {
        stage('Start') {
            steps {
                sh 'Starting proccess'
                sh 'echo my first jenkinsfile'
            }
        }
        stage('CheckNodeVer') { 
            steps {
                sh 'Checking the node version'
                sh '/usr/local/bin/node -v'
            }
        }
        stage('Build') { 
            steps {
                sh 'Building application'
                sh 'node /usr/local/bin/app.js'
            }
        }
        stage('Exit') {
            steps {
                sh 'Finishing'
                sh 'exit 1'
            }
        }
    }
}