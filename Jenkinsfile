pipeline {
    agent { docker { image 'node:6.3' } }
    stages {
        stage('test') {
            steps {
                sh 'npm --version'
            }
        }
    }
}