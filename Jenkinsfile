pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'Hello, Im Dev from Test Branch'
                sh 'git --version'
            }
        }
        stage('Prod') {
            steps {
                echo 'Hello, Im Prod from Test Branch'
                sh 'python3 --version'
            }
        }  
        stage('test') {
            steps {
                echo 'Hello, Im Test from Test Branch'
                sh 'docker --version'
            }
        }
    }
}