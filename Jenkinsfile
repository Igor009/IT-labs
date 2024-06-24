pipeline {
    agent any
    stages {
        stage('Check') {
            steps {
                sh './gradlew clean check -s'
            }
        }
        stage('Test') {
            steps {
                sh './gradlew clean test -s'
            }
        }
        stage('Build') {
            steps {
                sh './gradlew clean build -s'
            }
        }
    }
}