pipeline {
  agent any
  stages {
    stage('Build') {
        steps {
            echo 'Build the Application...'
            sh "pwd"
            sh "npm install"
        }
    }
    stage('Test') {
        steps {
            echo 'Test the Application...'
            sh "npm test"
        }
    }
    stage('Deploy') {
        steps {
            echo "Deploying the application..."
        }
    }
  }
}