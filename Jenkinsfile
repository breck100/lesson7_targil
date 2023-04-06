pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/breck100/lesson7_targil.git'
                bat 'python.exe main.py'
            }
        }
    }
}
