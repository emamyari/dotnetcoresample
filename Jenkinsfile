pipeline {
    agent any

    stages {
        stage('Build and Push Docker Image') {
            steps {
                script {
                    def dockerImageName = 'saeed:latest'

                    sh "docker build -t $dockerImageName ."
  
                   
                }
            }
        } 
    }
}