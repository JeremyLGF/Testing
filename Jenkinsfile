pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Running build stage'
        // Add your build commands here (e.g., sh "mvn clean install")
        //checkout scm //Checkout scm does a git checkout if SCM type is Git
      }
    }
    stage('Test') {
      steps {
        echo 'Running test stage'
        // Add your test commands here (e.g., sh "mvn test")
      }
    }
    stage('Deploy') {
      steps {
        echo 'Running deploy stage'
        // Add your deployment commands here (e.g., sh "scp -r ./dist/ user@host:/path/to/webserver")
      }
    }
  }
}
