pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
<<<<<<< HEAD
                git 'https://github.com/polanayukesh/sample-flask-app.git'
=======
                git 'https://github.com/polanayukesh/sample-app-demo-testing.git'
>>>>>>> 034cca9 (modified jenkins)
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

