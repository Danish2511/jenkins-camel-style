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

        stage('Package') {
            steps {
                sh 'echo Packaging artifact'
            }
        }
    }

    post {
        always {
            echo 'Pipeline finished'
        }
    }
}
