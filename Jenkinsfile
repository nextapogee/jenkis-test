pipeline {
    agent { docker 'web1' }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}