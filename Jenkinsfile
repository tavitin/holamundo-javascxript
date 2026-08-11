pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Descargando codigo desde GitHub...'
            }
        }

        stage('Ejecutar') {
            steps {
              //ejecuntando codigo de js
                bat 'node index.js'
            }
        }
    }
}
