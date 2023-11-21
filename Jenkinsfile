pipeline {
  agent any
  stages {
    stage('Development') {
      steps {
        sh 'echo "CI Procees and Deploy to Development"'
      }
    }

    stage('Staging') {
      steps {
        echo 'Promote to Staging Environment'
      }
    }

  }
}
