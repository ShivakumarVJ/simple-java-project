pipeline {
    agent any

    stages {
      stage('checkout') {
            steps {
                sh 'hostname'
            }
        }
        stage('Build') {
            steps {
                sh 'maven clean install'
            }
        }
        stage('Test') {
            steps {
                sh 'sleep 30'
            }
        }
        stage('Deploy') {
            steps {
                sh 'sleep 30'
            }
        }
    }
}
