pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                echo '🔧 Build en cours...'
            }
        }
        stage('Test') {
            steps {
                echo '🧪 Tests...'
                bat 'python test_app.py'
            }
        }
    }
}
