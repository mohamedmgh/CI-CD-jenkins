pipeline {
    agent any
    triggers {
        pollSCM('* * * * *') // toutes les minutes
    }
    stages {
        stage('Build') {
            steps {
                echo 'Builds...'
            }
        }
        stage('Test') {
            steps {
                bat 'python test_app.py'
            }
        }
    }
}
