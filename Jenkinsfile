pipeline {
    agent any
    tools {
        gradle "gradle"
    }
    stages {
        stage('Build') {

            steps {
                echo 'Building..'
                sh 'gradle --version'
                sh 'gradle clean build --stacktrace'
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
