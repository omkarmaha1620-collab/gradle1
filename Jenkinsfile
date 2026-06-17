pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/omkarmaha1620-collab/gradle1.git'
            }
        }

        stage('Build') {
            steps {
                sh 'gradle build'
            }
        }

        stage('Run') {
            steps {
                sh 'gradle run'
            }
        }
    }
}
