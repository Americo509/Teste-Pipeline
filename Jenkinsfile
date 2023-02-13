pipeline {
    agent any
        stage('triggerTrunk') {
            steps {
                build job: "prServer", wait: true
		}
	}
}