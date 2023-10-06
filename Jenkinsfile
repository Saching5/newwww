pipeline {
    agent any
    
    stages {
        stage('clone source code') {
            steps{
                git credentialsId: 'jenkins', url: 'https://github.com/MithunTechnologiesDevOps/maven-standalone-application.git'
            }
        }
        stage('software build using maven'){
            steps{
                echo 'building maven'
            }
        }
        stage('testing using sonaecube'){
            steps{
                echo 'testing using sonarcube'
            }
        }
        stage('deploying using ansible'){
            steps{
                echo 'deplying using ansible'
            }
        }
        stage('send confirmation email'){
            steps{
                echo 'sending confirmation email'
            }
        }
    }
}
