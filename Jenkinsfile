pipeline {
    agent any

    stages {
        stage('Print Build Number') {
            steps {
                script {
                    echo "Build_Number: ${BUILD_NUMBER}"
                }
            }
        }
        stage('List Files') {
            steps {
                script {
                    sh 'ls -al'
                }
            }
        }
    }
}
