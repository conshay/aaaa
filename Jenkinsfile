pipeline {
agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/conshay/aaa.git'
            }
        }
        stage('build') {
            steps {
                bat 'lesson8.py'
            }
        }
    }
}
