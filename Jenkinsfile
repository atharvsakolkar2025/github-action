pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git branch: 'main', url: 'https://github.com/atharvsakolkar2025/myjenkins.git'
                sh 'touch 1234'   // or npm install, etc.
            }
        }

        stage('Test') {
            steps {
                sh 'touch 2222'
            }
        }

        stage('Deploy') {
            steps {
                sh 'touch 1111'
               
            }
        }
    }
}

