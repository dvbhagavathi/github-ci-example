pipeline {
    agent { docker { image 'python:3.7.7-slim' } }
    stages {
        stage('build') {
            steps {
                sh 'python test.py'
            }
        }
    }
}
