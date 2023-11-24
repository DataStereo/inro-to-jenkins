pipeline {
    agent { docker { image 'docker/getting-started' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
