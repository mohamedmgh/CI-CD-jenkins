pipeline {
    agent any
    triggers {
        pollSCM('* * * * *') // toutes les minutes
    }
    stages {
        stage('Build') {
            steps {
                echo 'Build...'
            }
        }
        stage('Test') {
            steps {
                bat 'python test_app.py'
            }
        }
    }
}
