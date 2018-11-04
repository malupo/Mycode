pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                
                checkout scm
                   sh "./gradlew -version"
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
