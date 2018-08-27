pipeline {
    agent any
    tool name: 'gradle', type: gradle
    stages {
        stage('Build') {
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
