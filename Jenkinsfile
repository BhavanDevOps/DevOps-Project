pipeline {
    agent any
    stages {
        stage('Docker Install') {
            steps { 
                echo 'Docker Installing'
                sh 'apt-get install docker.io'
                sh 'docker --version'
            }
        }
    }
}
