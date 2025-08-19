pipeline {
    agent any
<<<<<<< HEAD

=======
    
>>>>>>> c870f801d433c38721c878da76107a083e286dc1
    stages {
        stage('Checkout') {
          steps {
            git branch: 'main', url: 'https://github.com/Kimayaahire/jenkins-ci-demo.git'
          }
<<<<<<< HEAD
        }
=======
        }  
>>>>>>> c870f801d433c38721c878da76107a083e286dc1
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
<<<<<<< HEAD
}
=======
}
>>>>>>> c870f801d433c38721c878da76107a083e286dc1
