pipeline {
   agent any

  stages {

    stage('Build') {
        steps {
          echo "build from github  ++webhook"
        }
      
    }
    stage('Test') {
      steps {
        echo "test from github plus webhook"
      }
    }
    stage('Deploy') {
      steps {
        echo "deploy from github bhaiiii +hokeee ye kiya hai humne ye plus webhook"
      }
    }
    
  }
  post {
    success {
      echo "ye bhi hua hamara success// Webhook working fine - testing again
  "
    }
    failure {
      echo " ye to hua hamara failure"
    }
  }
}













  

