pipeline {
    agent any

    stages {

        stage('Build & Test') {
            steps {
                sh 'javac main.java'
                sh 'java main'
            }
        }

        stage('Notify') {
            steps {
                echo "Pipeline Completed Successfully"
            }
        }
    }
}
