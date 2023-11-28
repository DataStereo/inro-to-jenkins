pipeline {
    agent {
        label '!windows'
    }

    environment {
        DISABLE_AUTH = 'true'
        DB_ENGINE    = 'sqlite'
    }

    stages {
        stage('Build') {
            steps {
                echo "Database engine is ${DB_ENGINE}"
                echo "DISABLE_AUTH is ${DISABLE_AUTH}"
                sh 'printenv'
            }
        }
    }
    post {
    success {
        mail to: 'morozov89oleg@gmail.com',
             subject: "Success Pipeline: ${currentBuild.fullDisplayName}",
             body: "Build config ${env.BUILD_URL}"
        }
    }
}
