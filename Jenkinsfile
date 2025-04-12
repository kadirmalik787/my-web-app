pipeline {
   agent any

  stages {

    stage('Build') {
        steps {
          echo "build from github"
        }
      
    }
    stage('Test') {
      steps {
        echo "test from github"
      }
    }
    stage('Deploy') {
      steps {
        echo "deploy from github bhaiiii"
      }
    }
    
  }
  post {
    success {
      echo "ye bhi hua hamara success "
    }
    failure {
      echo " ye to hua hamara failure"
    }
  }
}













  

