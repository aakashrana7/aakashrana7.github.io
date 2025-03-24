pipeline {
    agent any
    stages {
        stage('Clone Repository') {
            steps {
                git branch: 'main', url: 'https://github.com/aakashrana7/aakashrana7.github.io.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Building the project...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the project...'
            }
        }
    }
}
