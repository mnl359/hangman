pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        nodejs('nodejs') {
          sh 'npm install'
          sh 'npm run build'
        }

      }
    }

    stage('test') {
      steps {
        echo 'unit test'
      }
    }

  }
}