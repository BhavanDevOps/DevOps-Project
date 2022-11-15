pipeline {
    agent any
    stages {
        stage('Docker Install') {
            steps { 
                echo 'Docker Installing'
                sh 'apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin'
                sh 'docker --version'
            }
        }
    }
}
