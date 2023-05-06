pipeline {
    agent any

    stages {
      stage('checkout') {
            steps {
                git 'https://github.com/ShivakumarVJ/simple-java-project.git'
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
