pipeline {
    agent any
    stages {
        stage('Docker Install') {
            steps { 
                echo 'Docker Installing'
                sh 'sudo apt install docker.io'
                sh 'docker --version'
            }
        }
    }
}
