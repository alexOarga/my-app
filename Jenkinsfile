pipeline {
    agent { docker { image 'node:6.9.2' } }
    stages {
        stage('build') {
            steps {
                sh 'npm i -g npm@3.10.10'
            }
        }
    }
}
