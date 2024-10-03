pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/nithingowdahm87/dynamic_application'
            }
        }
        stage('Run Docker Compose') {
            steps {
                script{
                    sh 'docker-compose up -d'
                }
            }
        }
    }
}
