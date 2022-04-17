pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                nginx/conconfigure
                
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