pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                // Checkout the source code from the repository
                checkout scm
            }
        }

        stage('Compile') {
            steps {
                // Compile the Java source file
                sh 'javac MyApp.java'
            }
        }

        stage('Test') {
            steps {
                // Run any tests (if applicable)
                sh 'java MyApp'
            }
        }

        stage('Deploy') {
            steps {
                // Deploy the application (simplified example)
                sh 'java MyApp'
            }
        }
    }
}
