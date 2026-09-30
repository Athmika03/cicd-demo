pipeline {
    agent any

    stages {

        stage('Docker Build') {
            steps {
                bat 'docker build -t cicd-demo .'
            }
        }

        stage('Docker Run') {
            steps {
                bat 'docker run --rm cicd-demo'
            }
        }
    }
}