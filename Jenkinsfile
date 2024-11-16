pipeline {
    agent any
    environment {
        PATH = "/home/saitharakdev/.nvm/versions/node/v22.11.0/bin/node" 
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}