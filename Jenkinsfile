pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'Hello, Im Dev from Main Branch'
                sh 'git --version'
            }
        }
        stage('Prod') {
            steps {
                echo 'Hello, Im Prod from Main Branch'
                sh 'python3 --version'
            }
        }  
        stage('test') {
            steps {
                echo 'Hello, Im Test from Main Branch'
                sh 'docker --version'
            }
        }
    }
}