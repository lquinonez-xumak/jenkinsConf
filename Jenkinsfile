pipeline {
    agent {
        docker {
            image 'registry.xumak.gt:5000/lord-abbett/aem63:1.0.0'
            args '-p 4502:4502'
        }
    }
    stages {
        stage('Stage 1') {
            agent {
                docker.image('registry.xumak.gt:5000/lord-abbett/aem63:1.0.0').withRun('-p 4502:4502')
            }
            steps {

                echo 'hola mundo'
            }
        }
    }
}
