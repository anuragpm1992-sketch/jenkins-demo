pipeline {
    agent any

    stages {

        stage('Clone Code') {
            steps {
                echo "Fetching code from GitHub..."
                git 'https://github.com/anuragpm1992-sketch/jenkins-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Building application..."
                sh 'echo Build successful'
            }
        }

        stage('Test') {
            steps {
                echo "Running tests..."
                sh 'echo All tests passed'
            }
        }

    }
}
