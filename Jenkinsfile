pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Código baixado do GitHub com sucesso'
            }
        }

        stage('Build') {
            steps {
                echo 'Buildando aplicação...'
            }
        }

        stage('Test') {
            steps {
                echo 'Rodando testes...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploy no Kubernetes...'
            }
        }
    }
}
