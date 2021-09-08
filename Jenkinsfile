pipeline {
  agent any
  stages {
    stage('Build') {
        steps {
            echo 'Build the Application...'
            yarn install
        }
    }
    stage('Test') {
        steps {
            echo 'Test the Application...'
            yarn test
        }
    }
    stage('Deploy') {
        steps {
            echo "Deploying the application..."
        }
    }
  }
}