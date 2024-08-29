pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Example of a build step using Maven
                sh 'mvn clean compile'
            }
        }
        
        stage('Test') {
            steps {
                echo 'Testing...'
                // Example of a test step using Maven
                sh 'mvn test'
            }
        }
    }
}
