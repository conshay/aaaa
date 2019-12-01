pipeline {
agent any
    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/conshay/aaaa.git'
            }
        }
        stage('build') {
            steps {
                bat 'lesson8.py'
            }
        }
    }
}
