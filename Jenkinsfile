pipeline{
  agent any
}
Stages{
  stage('checkout'){
    steps{
      checkout scm
    }
  }
  stage('build'){
    steps{
      sh "mvn clean install"
    }
  }
}
