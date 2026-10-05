pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'THIRD'
                sh 'ls -la'
                sleep 60
                echo "This is MAIN branch"
            }
        }
    }
}
