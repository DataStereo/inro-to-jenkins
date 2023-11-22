node {
    stage('Build') {
        docker.image('3.9.5-amazoncorretto-8-debian-bookworm').inside {
            sh 'mvn --version'
        }
    }
}
