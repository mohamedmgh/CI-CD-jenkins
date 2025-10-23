pipeline {
    agent any
    triggers {
        pollSCM('* * * * *') // toutes les minutes
    }
    stages {
        stage('Build') {
            steps {
                echo 'Buildss...'
            }
        }
        stage('Test') {
            steps {
                bat 'python test_app.py'
            }
        }
    }
}
