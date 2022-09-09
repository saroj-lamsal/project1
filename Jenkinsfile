pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'javac jenkins.java'
            }
        }
         stage('output') {
            steps {
                bat 'java test'
            }
        }
        
    }
}
