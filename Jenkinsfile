pipeline {
    agent any
    
    stages {
        stage('Build') {
            
            steps {
                echo 'Building..'
                tool name: 'gradle-4.7', type: 'gradle'
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
