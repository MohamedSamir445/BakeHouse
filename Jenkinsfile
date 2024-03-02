pipeline {
    agent any

    stages {
        stage('Echo Build Number') {
            steps {
                echo "Build Number: ${env.BUILD_NUMBER}"
            }
        }
        stage('List Directory') {
            steps {
                sh 'ls'
            }
        }
    }
}
