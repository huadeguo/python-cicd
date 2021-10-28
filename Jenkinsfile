pipeline {
    agent any
    stages {
        stage('Git-Checkout') {
			steps {
				echo "aqtj获获得资源获得资源ylk获得资源库 ";
				git branch: 'master', url: 'https://github.com.cnpmjs.org/huadeguo/python-cicd.git'
			}
		}
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
