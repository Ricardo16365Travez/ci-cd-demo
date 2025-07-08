pipeline {
    agent any

    stages {
        stage('Clonar') {
            steps {
                git branch: 'main', url: 'https://github.com/Ricardo16365Travez/ci-cd-demo.git'
            }
        }
        stage('Ejecutar') {
            steps {
                bat 'python main.py'
            }
        }
    }
}
