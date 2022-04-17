pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                sh 'cd nginx'
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