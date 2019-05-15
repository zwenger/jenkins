pipeline {
    agent any
    stages {
        stage("Hola") {
            steps {
                echo 'Hola Mundo desde github'
                slackSend color: 'good', message: 'HOLA PIBE EL BUILD SALIO BIEN'
            }
        }
    }
}
