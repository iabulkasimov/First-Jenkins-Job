pipeline {
    agent {
    docker {
        image 'maven:3-alpine'
        label 'docker'
    }
}
    stages {
        stage('run') {
            steps {
                echo 'Clarusway_Way to Reinvent Yourself'
                sh 'python3 --version'
                sh 'python3 pipeline.py'
            }
        }
    }
}


