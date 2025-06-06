pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/siri666519/jenkins-demo.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}


