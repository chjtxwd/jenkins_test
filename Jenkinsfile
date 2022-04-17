pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                curl http://nginx.org/download/nginx-1.21.6.tar.gz
                tar -xvf nginx-1.21.6.tar.gz
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