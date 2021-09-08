pipeline {
  agent any
  tools {nodejs "nodejs"}
  stages {
    stage('Build') {
        steps {
            echo 'Installing Dependencies...'
            sh "yarn install"
            echo 'Building the Application...'
            sh "yarn build"
        }
    }
    stage('Test') {
        steps {
            echo 'Testing the Application...'
            sh "yarn test"
        }
    }
    stage('Deploy') {
        steps {
            echo "Deploying the application..."
        }
    }
  }
}