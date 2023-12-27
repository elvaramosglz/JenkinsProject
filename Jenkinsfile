pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Hello, this is the Build stage"
                // Your build commands go here
            }
        }

        stage('Test') {
            steps {
                echo "Hello, this is the Test stage"
                // Your test commands go here
            }
        }

        stage('Deploy') {
            steps {
                echo "Hello, this is the Deploy stage"
                // Your deployment commands go here
            }
        }
    }

    post {
        success {
            echo "Pipeline executed successfully. You can add post-success actions here."
        }
        failure {
            echo "Pipeline failed. You can add post-failure actions here."
        }
    }
}
