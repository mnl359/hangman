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

  }
}