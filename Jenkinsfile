pipeline {
    agent {          
        pool {
            name 'ALL'      
        }
    }

    deployEnv '00-test'

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
