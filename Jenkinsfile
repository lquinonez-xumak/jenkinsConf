pipeline {
    agent none
    stages {
        stage('Stage 1') {
            agent {
                docker.image('registry.xumak.gt:5000/lord-abbett/aem63:1.0.0')
            }
            steps {

                echo 'hola mundo'
            }
        }
    }
}
