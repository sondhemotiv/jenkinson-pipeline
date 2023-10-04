pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
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
        stage('Clone') {
            steps {
                git 'https://github.com/sondhemotiv/jenkinson-pipeline.git'
            }
        }
    }
}