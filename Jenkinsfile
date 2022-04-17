pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'nginx/configure'
                sh 'nginx/make'
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