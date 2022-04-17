pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'cd nginx'
                sh 'configure'
                sh 'make'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}