pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git 'https://github.com/your-username/wordpress-docker-cicd.git'
            }
        }

        stage('Run Docker') {
            steps {
                sh 'docker-compose up -d'
            }
        }
    }
}
