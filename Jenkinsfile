pipeline {
    agent any

    stages {

        stage('Clone') {
            steps {
                echo 'Cloning repository...'
            }
        }

        stage('Build') {
            steps {
                echo 'Building website...'
            }
        }

        stage('Deploy') {
            steps {
                bat 'xcopy E Y  Cdeploy'
            }
        }

    }
}