pipeline {
    agent any
    environment {
        PATH = "/home/saitharakdev/.nvm/versions/node" 
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}