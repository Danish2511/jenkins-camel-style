pipeline {
    agent any

    stages {
        stage('Init') {
            steps {
                echo 'Pipeline started'
            }
        }

        stage('Build') {
            steps {
                sh 'echo Building like a Camel route'
            }
        }

        stage('Test') {
            steps {
                sh 'echo Testing completed'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished'
        }
    }
}
