pipeline {
    agent any
    stages {
        stage('Lint HTML') {
            steps {
                sh 'tidy -q -e index.html'
            }
        }
        stage('Upload to Azure') {
            steps {
		    sh 'echo "Hello World with AZ creds"'
            }
        }
    }
}
