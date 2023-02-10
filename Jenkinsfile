pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('triggerTrunk') {
            steps {
                build job: "Teste - Pipeline (Release)", wait: true
            }
        }
    }
}