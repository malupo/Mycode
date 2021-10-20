pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                





                /* comment 10-20-21  */

                /* comment */

                checkout scm
                   shell "gradlew.bat -version"
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
