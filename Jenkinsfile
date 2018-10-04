pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'npm3 --version'
            }
        }
    }
}

node {
    checkout scm
}
