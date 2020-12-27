pipeline {
    agent any
    stages {
        stage('hello AWS') {
            steps {
                withAWS(credentials: 'jenkins', region: 'us-west-1') {
                sh '/usr/local/bin/aws secretsmanager list-secrets'
                }
            }
        }
    }
}
