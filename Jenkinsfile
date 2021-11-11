pipeline {
  agent any
  stages {
    stage('Lint HTML') {
      parallel {
        stage('Lint HTML') {
          steps {
            sh 'tidy -q -e index.html'
          }
        }

        stage('Another Linting') {
          steps {
            sh 'ls'
          }
        }

      }
    }

    stage('Upload to Azure') {
      steps {
        sh 'echo "Hello World with AZ creds"'
      }
    }

  }
}