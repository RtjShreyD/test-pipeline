pipeline {
    agent { lable 'agent1' }
    
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
