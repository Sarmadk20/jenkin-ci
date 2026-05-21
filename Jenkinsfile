pipeline {
    agent any

    stages {

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
