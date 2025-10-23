pipeline {
    agent any
    triggers {
        pollSCM('* * * * *') // toutes les minutes
    }
    stages {
        stage('Build') {
            steps {
<<<<<<< HEAD
                echo 'Build...'
=======
                echo '🔧 Build en coursss...'
>>>>>>> efd9ff5bab77e7e85c400aae936915f5eb3f5dad
            }
        }
        stage('Test') {
            steps {
                bat 'python test_app.py'
            }
        }
    }
}
