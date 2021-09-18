pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/Abhishek1121-tech/DMSAPP.git', branch: 'master', changelog: true)
      }
    }

    stage('Build') {
      steps {
        sh 'mvn clean install'
      }
    }

  }
}