pipeline {
    agent any

    stages {
        stage('Pre-Build') {
            steps{
                sh 'id'
            }
        }
        stage('Build') {
            steps {
                sh 'pwd'
                sh './configure'
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