pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                bat '"C:\\Users\\HP\\AppData\\Local\\Python\\bin\\python.exe" app.py'
            }
        }

        stage('Test') {
            steps {
                echo 'Test stage completed'
            }
        }
    }
}