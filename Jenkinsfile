pipeline {
    agent {
        docker {
            image 'node:6-alpine' 
            args '-p 3000:3000' 
        }
    }
    stages {
        stage('Install Dependancies') { 
            steps {
                sh 'npm install' 
            }
        }
        stage('Copy Configurations') { 
            steps {
                sh '' 
            }
        }
        stage('Build') { 
            steps {
                sh 'l' 
            }
        }
        stage('Backup previouse build') { 
            steps {
                sh 'l' 
            }
        }
        stage('Roll in new build') { 
            steps {
                sh '' 
            }
        }
        stage('NGINX restart') { 
            steps {
                sh '' 
            }
        }
        stage('verify') { 
            steps {
                sh '' 
            }
        }
    }
}