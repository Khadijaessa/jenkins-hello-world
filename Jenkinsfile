      pipeline {
          agent any
          stages {
              stage('Build') {
                  steps {
                      script {
                        bat 'echo "Running on Windows"'
                        bat 'python hello.py'
                        bat 'javac HelloWorld.java'
                        bat 'java HelloWorld'
                      }
                  }
              }
          }
      }
