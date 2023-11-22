node {
    stage('Build') {
        docker.image('maven:3.9.5-eclipse-temurin-17-alpine').inside {
            sh 'mvn --version'
        }
    }
}
