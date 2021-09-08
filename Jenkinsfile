pipeline {
  agent any
  tools {nodejs "nodejs"}
  stages {
    stage('Build') {
        steps {
            echo 'Installing Dependencies...'
            sh "npm install"
            echo 'Building the Application...'
            sh "npm run build"
        }
    }
    stage('Test') {
        steps {
            echo 'Testing the Application...'
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