pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Replace with actual build command
                bat 'start /b my_script.bat'
            }
        }

        stage('Test') {
            steps {
                // Replace with test command
                sh 'mvn test'
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
