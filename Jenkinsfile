pipeline {
    agent {          
        pool {
            name 'ALL-1-2-3'      
        }
    }

    deployEnv 'krill_env'

    options {
        disableConcurrentBuilds()
    }

    stages {
        stage('Hello') {
            steps {
                sleep 70
            }
        }
    }
}
