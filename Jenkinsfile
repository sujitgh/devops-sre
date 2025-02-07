pipeline {
    agent any
    stages {
        stage('npm version check') {
            steps {
                sh '''
                    node -v
                    npm -v
                '''
            }
        }
        
}