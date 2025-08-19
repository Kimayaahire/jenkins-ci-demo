pipeline {
    agent any

    stages {
        stage('Checkout') {
          steps {
            git branch: 'main', url: 'https://github.com/Kimayaahire/jenkins-ci-demo.git'
          }
        }
        stage('Build') {
            steps {
                sh 'npm install'  // Example build command
            }
        }
        stage('Test') {
            steps {
                sh 'npm test'  // Example test command
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'mkdir -p deploy && cp -r * deploy/'
            }
        }
    }
}