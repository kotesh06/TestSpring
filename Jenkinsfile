pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                 echo 'Test Kotesh..'
                echo "M2_HOME=%M2_HOME%"
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
