pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Código baixado do GitHub com sucesso'
            }
        }

        stage('Build Docker Image') {
            steps {
                sh 'docker build -t devops-lab-nginx:latest .'
            }
        }

        stage('Test') {
            steps {
                echo 'Imagem Docker criada com sucesso'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Próximo passo: deploy no Kubernetes'
            }
        }
    }
}
