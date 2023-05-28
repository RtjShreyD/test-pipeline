pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git branch: 'main', credentialsId: 'rtjgithub_pa_token', url: 'https://github.com/RtjShreyD/test-pipeline.git'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Build Started"'
                sh 'docker --version'
            }
        }
    }
}
