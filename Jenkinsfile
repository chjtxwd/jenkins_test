pipeline {
    agent any

    stages {
        stage('Pre-Build') {
            steps{
                sh 'id'
                sh 'sudo yum -y install pcre-devel openssl openssl-devel'
            }
        }
        stage('Build') {
            steps {
                sh 'pwd'
                sh './configure'
                sh './make'
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