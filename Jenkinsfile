pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {



                git 'https://github.com/polanayukesh/sample-app-demo-testing.git'

            }
        }

        stage('Build') {
            steps {
                sh 'pip install -r requirements.txt'
            }
        }

        stage('Test') {
            steps {
                sh 'echo "No tests yet"'
            }
        }

        stage('Docker Build') {
            steps {
                sh 'docker build -t sample-flask-app:latest .'
            }
        }
    }
}

