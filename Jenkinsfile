pipeline {
    agent {
        docker {
            image 'node:lts-buster-slim'
            args '-p 3000:3000'
        }
    }
    environment {
        HOME = '.'
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
            }
        }
        
    }
    stages {
        stage('Test') {
            steps {
                sh 'npm run'
            }
        }
        
    }
}
