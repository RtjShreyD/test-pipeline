pipeline {
    agent { label 'agent1' }
    
    stages {
        stage('Checkout') {
            steps {
                sh '''
                  docker version
                  docker compose version
                 '''
            }
        }
    }
}
