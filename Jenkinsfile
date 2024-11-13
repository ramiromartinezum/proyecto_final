// Jenkinsfile
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                // Instalar dependencias si es necesario
                // Ejecutar el script principal
                bat "echo %PATH%"
                bat 'python3 main.py'
            }
        }
    }
}
