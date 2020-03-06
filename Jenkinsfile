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
        sh 'echo "Testing..."'
      }
    }

    stage('deploy') {
      steps {
        sh 'echo "Deploying..."'
      }
    }

  }
}