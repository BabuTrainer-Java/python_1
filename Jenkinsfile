pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                echo 'Installing dependencies'
                bat 'pip install -r requirements.txt'
            }
        }
        stage('hello') {
            steps {
                sh 'python hello.py'
            }
        }


    }
}
