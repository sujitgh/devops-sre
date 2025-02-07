pipeline {
    agent any
    tools {
        nodejs 'nodejs-20.6.0'
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