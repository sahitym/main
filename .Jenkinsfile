// Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any // Defines where the pipeline will run (any available agent).

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                
            }
        }
    }
    post { // Actions to take after the pipeline runs (success or failure).
        success {
            echo 'Pipeline completed successfully.'
        }
        failure {
            echo 'Pipeline failed.'
        }
    }
}