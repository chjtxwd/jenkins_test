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
                sh 'objs/nginx'
                sh 'curl 127.0.0.1'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}