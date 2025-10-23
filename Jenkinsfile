pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Build') {
            steps {
                echo '🔧 Build en coursss...'
            }
        }
        stage('Test') {
            steps {
                echo '🧪 Testss..'
                bat 'python test_app.py'
            }
        }
    }
}
