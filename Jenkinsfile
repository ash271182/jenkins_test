pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                // Your build steps go here
                echo 'Building...'
                sh 'docker build -t myjenkins-blueocean:2.426.2-1 .'
            }
        }
        stage('Test') {
            steps {
                // Your test steps go here
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                // Your deployment steps go here
                echo 'Deploying...'
            }
        }
    }
}
