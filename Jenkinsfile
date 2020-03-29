pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World after a new git commit and a new ending"'
                sh '''
                    echo "Multiline shell steps works too again"
                    ls -lah
                '''
            }
        }
    }
}
