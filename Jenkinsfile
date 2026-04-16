pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'Hello, Im Dev from Prod Branch'
                sh 'git --version'
            }
        }
        stage('Prod') {
            steps {
                echo 'Hello, Im Prod from Prod Branch'
                sh 'python --version'
            }
        }  
        stage('test') {
            steps {
                echo 'Hello, Im Test from Prod Branch'
                sh 'docker --version'
            }
        }
    }
}