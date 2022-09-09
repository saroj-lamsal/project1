pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                bat 'python deploy.py'
            }
        }
         stage('output') {
            steps {
                echo "hello hi"
            }
        }
        
    }
}
