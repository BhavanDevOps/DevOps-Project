pipeline {
    agent any
    stages {
        stage('Git Version Checkout') {
            steps { 
                echo 'Git Installing'
                sh 'git --version'
            }
        }
        stage('Docker Installation'){
            steps{
                echo 'Docker Installing'
                sh 'apt-get remove docker docker-engine docker.io'
                sh 'apt-get update -y'
                sh 'apt install docker.io -y'
                sh 'docker --version'
            }
        }
    }
}
