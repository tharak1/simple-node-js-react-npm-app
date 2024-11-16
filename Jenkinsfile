pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                sh '''
                    sudo apt update
                    sudo apt install -y nodejs npm
                '''
            }
        }
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
