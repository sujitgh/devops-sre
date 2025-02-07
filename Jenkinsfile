pipeline {
    agent any
    stages('npm version check'){
        steps{
            sh '''
            node -v
            npm -v
            '''
        }
    }
}