pipeline {
   agent any

  stages {

    stage('Build') {
        steps {
          echo "build from github  ++hoke"
        }
      
    }
    stage('Test') {
      steps {
        echo "test from github +hoke"
      }
    }
    stage('Deploy') {
      steps {
        echo "deploy from github bhaiiii +hokeee ye kiya hai humne ye"
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













  

