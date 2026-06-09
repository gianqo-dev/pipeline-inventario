pipeline {
    agent any

    stages {

        stage('Inicio') {
            steps {
                echo 'Iniciando Pipeline'
            }
        }

        stage('Validacion') {
            steps {
                bat 'python scripts\\validacion.py'
            }
        }

        stage('Finalizacion') {
            steps {
                echo 'Pipeline ejecutado correctamente'
            }
        }
    }
}