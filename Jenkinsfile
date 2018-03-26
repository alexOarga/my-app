pipeline {
    agent { docker { image 'node:6.9.2' } }
    stages {
        stage('build') {
            steps {
                sh 'npm install'
            }
        }
    }
}
