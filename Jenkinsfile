pipeline {
    agent { docker { image 'node:14-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello there"'
                sh 'npm --version'
                sh '''
                    echo "Multiline"
                    ls -lf
                '''
            }
        }
    }
}
