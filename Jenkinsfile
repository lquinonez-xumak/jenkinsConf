pipeline {
    agent any
    stages {
        stage('Stage 1') {

            steps {
                docker.image('registry.xumak.gt:5000/lord-abbett/aem63:1.0.0').withRun('-p 4502:4502') {
                echo 'hola mundo'
                }
            }
        }
    }
}
