pipeline {
    agent {          
        pool {
            name 'all-in-one'      
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
