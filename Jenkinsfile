pipeline {
    agent any

    stages {
      stage('checkout') {
            steps {
                sh 'user -a'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
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
