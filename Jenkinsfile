pipeline {
    agent { docker { image 'maven-nodejs:3-jdk-17' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
