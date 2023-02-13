pipeline {
    agent any

    stages {
	stage('triggerTrunk') {
            steps {
                build job: "prServer", wait: true
            }
        }
    }
}