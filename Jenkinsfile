pipeline {
    agent { docker { image 'postgres:11.22-bullseye' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
