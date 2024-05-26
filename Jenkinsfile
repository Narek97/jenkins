// Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any

    stages {
        stage("Yarn"){
            steps{
                echo "yarn start"
                nodejs("nodejs-22.1.0"){
                    sh 'yarn'
                }
            }
        }
        stage('Build') {
            steps {
                echo 'Start Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Sтарт Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}