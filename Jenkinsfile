pipeline {
agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/Arkady-Karasin/JenkinsTest.git'
            }
        }
        stage('build') {
            steps {
               bat 'python 1.py'
            }
       
        }
    }
}

