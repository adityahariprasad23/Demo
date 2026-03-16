pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                git 'https://github.com/adityahariprasad23/Demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing project...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying project to server...'
            }
        }

    }
}
// trigger build
