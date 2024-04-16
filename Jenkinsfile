pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                // Checkout the code from the GitHub repository
                git 'https://github.com/asingh766/JenkinsIntegration.git'
            }
        }
        stage('Hello World') {
            steps {
                // Print "Hello World" message
                echo 'Hello World!'
            }
        }
    }
    
    // Triggers the pipeline to run when changes are pushed to the GitHub repository
    triggers {
        githubPush()
    }
}
J
