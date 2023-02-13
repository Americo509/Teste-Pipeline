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
                build job: "prServer", wait: true
            }
        }
    }
}