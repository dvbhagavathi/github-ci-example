pipeline {
    agent {
        docker 'python:3.7.7-slim'
    }
    stages {
        stage('build') {
            steps {
                sh 'python test.py'
            }
        }

    stage('get version') {
        steps {
            sh 'python --version'
        }
    }

    }
}
