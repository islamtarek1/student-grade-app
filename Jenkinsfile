
pipeline {
    agent any

    stages {
        stage('Run Python App') {
            steps {
                bat 'python --version'
                bat 'echo 95| python grades.py'
            }
        }
    }
}
