pipeline {
    agent any
    
    stages {
        stage('Checkout') {
            steps {
                echo '📥 Baixando código do repositório...'
                checkout scm
            }
        }
        
        stage('Build') {
            steps {
                echo '🏗️ Construindo a aplicação...'
                sh 'echo "Simulando build da aplicação"'
                sh 'ls -la'
            }
        }
        
        stage('Test') {
            steps {
                echo '🧪 Executando testes...'
                sh 'echo "Executando testes unitários"'
                sh 'echo "Todos os testes passaram!"'
            }
        }
        
        stage('Deploy') {
            steps {
                echo '🚀 Fazendo deploy...'
                sh 'echo "Aplicação deployada com sucesso!"'
            }
        }
    }
    
    post {
        success {
            echo '✅ Pipeline concluído com sucesso!'
        }
        failure {
            echo '❌ Pipeline falhou!'
        }
    }
}
