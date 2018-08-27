pipeline {
    agent any
    
    stages {
        stage('Build') {
            tool name: 'gradle', type: gradle
            steps {
                echo 'Building..'
                sh 'gradle clean build'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
