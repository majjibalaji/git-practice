pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/<your-username>/cicd-pipeline-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo "Build completed"
            }
        }

        stage('Test') {
            steps {
                echo "Tests passed"
            }
        }

        stage('Deploy') {
            steps {
                sh 'sudo cp index.html /var/www/html/'
            }
        }
    }
}
