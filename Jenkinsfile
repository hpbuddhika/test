Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'node:16.13.1-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello World !!!!!!!!!!!!!!!!!!!!!!"'
            }
        }
    }
}
