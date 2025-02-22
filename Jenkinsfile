pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/IfeanyiNjoku27/MavenProject.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying application...'
                // Add deployment steps here
            }
        }
    }
}

