pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Verify Source Code') {
            steps {
                sh 'ls -la'
                sh 'git log -1 --oneline'
            }
        }
    }
}
