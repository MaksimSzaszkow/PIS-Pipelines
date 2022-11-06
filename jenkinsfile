"Test pipeline for PiS project"
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building Project"'
            }
        }
        stage('Test') {
            steps {
                sh 'echo "Testing Project"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying Project..."'
            }
        }
    }
}