pipeline {
    agent any

    stages {
        stage('triggerAutomacao') {
            steps {
                echo scm.branches[0].name
                build job: "prServer", wait: true, parameters: [string(name: 'Branch', value: String.valueOf(scm.branches[0].name))]
            }
        }
    }
}