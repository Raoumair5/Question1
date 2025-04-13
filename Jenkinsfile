pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Raoumair5/Question1.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building static HTML project...'
            }
        }
        stage('Test') {
            steps {
                echo 'No real unit tests, simulating pass.'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployment step here.'
            }
        }
    }
}
