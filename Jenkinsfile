pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'Hello World'
        sh 'C:/DevTools/apache-maven-3.5.0/bin/mvn test'
      }
    }
    stage('install') {
      steps {
        sh 'C:/DevTools/apache-maven-3.5.0/bin/mvn install'
      }
    }
  }
}