pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/majjibalaji/git-practice'
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
