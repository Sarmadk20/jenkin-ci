pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                git 'https://github.com/Sarmadk20/jenkin-ci.git'
            }
        }

        stage('Build & Test') {
            steps {
                sh 'javac h.java'
                sh 'java h'
            }
        }

        stage('Notify') {
            steps {
                echo "Pipeline Completed Successfully"
            }
        }
    }
}