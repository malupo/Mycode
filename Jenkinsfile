pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                
                checkout scm
                   sh "gradlew.bat -version"
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
