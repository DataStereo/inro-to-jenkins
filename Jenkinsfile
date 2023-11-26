/* Requires the Docker Pipeline plugin */
pipeline {
    agent { docker { image 'maven:3.9.5-amazoncorretto-8-debian-bookworm' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
