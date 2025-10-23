pipeline {
    agent any
    triggers {
        pollSCM('* * * * *') // toutes les minutes
    }
    stages {
        stage('Build') {
            steps {
<<<<<<< HEAD
<<<<<<< HEAD
                echo 'Build...'
=======
                echo '🔧 Build en coursss...'
>>>>>>> efd9ff5bab77e7e85c400aae936915f5eb3f5dad
=======
                echo 'Builds...'
>>>>>>> b633f2df6468798d5dae9c50a43fbc4177984ca1
            }
        }
        stage('TestS') {
            steps {
                bat 'python test_app.py'
            }
        }
    }
}
