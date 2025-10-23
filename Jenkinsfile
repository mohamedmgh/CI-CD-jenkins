pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo '🔧 Build en cours...'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Exécution des tests...'
                bat 'python --version'
                bat 'python test_app.py'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Déploiement terminé (simulation)...'
            }
        }
    }

    post {
        success {
            echo '✅ Pipeline exécutée avec succès.'
        }
        failure {
            echo '❌ Une erreur est survenue.'
        }
    }
}
