pipeline {
    agent any

    stages {
        stage('First') {
            steps {
                echo 'First step'
                sh 'pwd'
                sh 'whoami'
            }
        }
        stage('Second') {
            steps {
                echo 'Second step'
                sh 'molecule test'
            }
        }
    }
}