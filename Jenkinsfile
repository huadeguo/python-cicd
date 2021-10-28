pipeline {
    agent any
    stages {
        
        stage('test') {
            steps {
                echo 'build test'
                bat 'python --version'
                bat 'pip install flask pytest'
                bat 'set pythonpath=src;pytest'
            }
        }
    }
}
