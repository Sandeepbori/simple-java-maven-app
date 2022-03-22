pipeline {
  agent any
stages {
  stage('checkout') {
    steps {
      checkout scm
    }
  }
  stage('build') {
    steps {
      sh "echo $PATH"
      sh "mvn clean install"
    }
  }
}
}
