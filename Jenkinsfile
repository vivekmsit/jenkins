pipeline {
    agent { docker 'ubuntu:18.04' }

    stages {
        stage('Build') {
            steps {
                echo 'Building.. 1'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
