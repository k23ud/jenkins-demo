pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Installing dependencies...'
                sh 'echo "build success!"'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                sh 'echo "tests passed!"'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'echo "deployed successfully!"'
            }
        }
    }
}

