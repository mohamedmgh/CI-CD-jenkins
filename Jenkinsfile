pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo '🔧 Étape Build...'
                bat 'python --version'
                bat 'echo Environnement prêt !'
            }
        }

        stage('Test') {
            steps {
                echo '🧪 Exécution des tests...'
                // ⚠️ remplace "test_app.py" par le nom exact de ton fichier test
                bat 'python test_app.py'
            }
        }

        stage('Deploy') {
            steps {
                echo '🚀 Déploiement terminé (simulation)...'
                bat 'echo Déploiement terminé !'
            }
        }
    }

    post {
        success {
            echo '✅ Pipeline exécuté avec succès !'
        }
        failure {
            echo '❌ Le pipeline a échoué ! Vérifie les logs Jenkins.'
        }
    }
}
