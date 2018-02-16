pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        echo 'Hello World'
        bat 'C:\\DevTools\\apache-maven-3.5.0\\bin\\mvn test'
      }
    }
    stage('install') {
      steps {
        bat 'C:\\DevTools\\apache-maven-3.5.0\\bin\\mvn install'
      }
    }
  }
}