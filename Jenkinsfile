pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building the project...'
                bat mvn test
            }
        }
        stage('Test') {
            steps {
                echo 'Testing the project...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
            }
        }
        stage('Release') {
            steps {
                echo 'Release the project...'
            }
        }
    }
}
