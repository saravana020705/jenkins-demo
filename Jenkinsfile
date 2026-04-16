pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building from Jenkinsfile in Git!'
                bat 'javac Hello.java'
            }
        }
        stage('Run') {
            steps {
                bat 'java Hello'
            }
        }
    }
}
