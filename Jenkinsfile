pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // Exemple de commande Windows
                bat 'echo Compilation terminée !'
            }
        }

        stage('Test') {
            steps {
                echo 'Running tests...'
                // Exemple de test (à adapter à ton projet)
                bat 'python --version'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
                bat 'echo Déploiement terminé !'
            }
        }
    }
}
