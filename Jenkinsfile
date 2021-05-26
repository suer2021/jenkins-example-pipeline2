pipeline {
    /* insert Declarative Pipeline here */
    agent any
    stages {
        stage('Deploy/Build App') {
            steps {
                bat '''
                    echo 'Application deployed successfully'
                '''
            }
        }
        stage('Frontend tests') {
            steps {
                bat 'echo %cd%'
                bat 'dir'
            }
        }
        stage('Backend tests') {
            steps {
                bat 'echo %cd%'
                bat 'dir'
            }
        }
        stage('Performance tests') {
            steps {
                bat 'echo %cd%'
                bat 'dir'
            }
        }
    }
}