      pipeline {
          agent any
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
