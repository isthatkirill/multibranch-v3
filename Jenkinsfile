pipeline {
    agent any

    deployEnv 'krill_env'

    options {
        disableConcurrentBuilds()
    }

    stages {
        stage('Hello') {
            steps {
                sleep 60
            }
        }
    }
}
