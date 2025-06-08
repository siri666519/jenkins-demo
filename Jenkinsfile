pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/siri666519/jenkins-demo.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean install'
            }
        }
    }
}


