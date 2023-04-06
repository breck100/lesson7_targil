properties([pipelineTriggers([pollSCM('* * * * *')])])
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/breck100/lesson7_targil.git'
                bat 'python.exe main.py'
            }
        }
        stage('Hello2') {
            steps {
               bat 'dir'
                echo "just testing"
            }
        }
    }
}
