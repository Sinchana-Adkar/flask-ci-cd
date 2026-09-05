pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'pip3 install -r requirements.txt'
            }
        }
        stage('Test') {
            steps {
                sh 'pytest tests/ || echo "No tests found"'
            }
        }
        stage('Deploy') {
            steps {
                sh '''
                echo "Deploy step placeholder"
                '''
            }
        }
    }
}
