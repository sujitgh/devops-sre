pipeline {
    agent any
    tools {
        nodejs 'nodejs-22-6-0'
    }
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
}