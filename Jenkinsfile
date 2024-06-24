      pipeline {
          agent any
          stages {
              stage('Build') {
                  steps {
                      script {
                        bat 'echo "Running on Windows"'
                        bat 'javac HelloWorld.java'
                        bat 'java HelloWorld'
                        bat 'python hello.py'
                      }
                  }
              }
          }
      }
