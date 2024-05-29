pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh '/usr/local/bin/node -v'
            }
        }
        stage('Test') { 
            steps {
                sh 'echo my first jenkinsfile'
            }
        }
        stage('Run') {
            steps {
                sh '/usr/local/bin/node app.js'
            }
        }
    }
}
