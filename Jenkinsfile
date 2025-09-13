pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/aishp411-pixel/TravelMemory.git'
            }
        }
        stage('Install') {
            steps {
                sh 'cd backend; npm install'
            }
        }
        stage('Build') {
            steps {
                sh 'cd backend; npm run build'
            }
        }
    }

}




