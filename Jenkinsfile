pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Khadijaessa/jenkins-hello-world.git'
            }
        }
        stage('Build') {
            steps {
                script {
                    if (isUnix()) {
                        sh 'echo "Running on Unix"'
                    } else {
                        bat 'echo "Running on Windows"'
                    }
                }
            }
        }
    }
}
