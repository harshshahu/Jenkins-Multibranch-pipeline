pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'Hello, Im Dev from Dev Branch'
                sh 'git --version'
            }
        }
        stage('Prod') {
            steps {
                echo 'Hello, Im Prod from Dev Branch'
                sh 'python3 --version'
            }
        }  
        stage('test') {
            steps {
                echo 'Hello, Im Test from Dev Branch'
                sh 'docker --version'
            }
        }
    }
}