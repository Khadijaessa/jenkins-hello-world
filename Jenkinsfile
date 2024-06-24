      pipeline {
          agent any
          environment {
              JAVA_HOME = "C:/Program Files/Java/jdk-21"
              PATH = "${env.JAVA_HOME}/bin:${env.PATH}"
    }
          stages {
              stage('Build') {
                  steps {
                      script {
                        bat 'python hello.py'
                        bat 'echo "Running on Windows"'
                        bat 'javac HelloWorld.java'
                        bat 'java HelloWorld'
                      }
                  }
              }
          }
      }
