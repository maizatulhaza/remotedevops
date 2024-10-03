pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Replace with actual build command
                 bat 'mvn clean install'
            }
        }

        stage('Test') {
            steps {
                // Replace with test command
                bat 'mvn test'
            }
        }
    }

    post {
        success {
            echo 'Pipeline executed successfully'
        }
        failure {
            echo 'Pipeline execution failed'
        }
    }
}
