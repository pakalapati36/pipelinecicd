pipeline {
  agent {
    label 'jdk9'
  }
  stages {
    stage('build1') {
      steps {
        echo "Hello ${MY_NAME}!"
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Mary'
  }
}