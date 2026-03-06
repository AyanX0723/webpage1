pipeline {
    agent any

    stages {

        stage('Clone Repository') {
            steps {
                git 'https://github.com/AyanX0723/Webpage.git'
            }
        }

        stage('Check Files') {
            steps {
                bat 'dir'
            }
        }

        stage('Build') {
            steps {
                bat 'echo Building Webpage'
            }
        }

    }
}