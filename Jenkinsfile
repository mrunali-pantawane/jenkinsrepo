pipeline {
    agent any

    stages {
        stage('dev') {
            steps {
                echo 'i am in development'
                sh 'docker --version'
            }
        }
            stage('stage') {
            steps {
                echo 'i am in stagging'
                sh 'php --version'
            }
        }
            stage('prod') {
            steps {
                echo 'i am in production'
                sh 'git --version'
            }
        }
    }
}
