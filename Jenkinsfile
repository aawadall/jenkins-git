pipeline {
    agent any
    stages {
        stage('Pre-Build') {
            steps {
                sh 'echo "Pre-Build"'
            }
        }
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}