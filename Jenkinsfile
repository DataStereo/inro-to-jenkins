pipeline {
    agent { docker { image '3.9.5-amazoncorretto-8-debian-bookworm' } }
    stages {
        stage('build') {
            steps {
                /bin/sh 'mvn --version'
            }
        }
    }
}
