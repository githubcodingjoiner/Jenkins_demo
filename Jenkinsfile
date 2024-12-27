pipeline{
  agent any
  stages{
    stage('Build'){
      step{
        echo "Building"
      }
    }
    stage('Test'){
      step{
        echo "Testing"
      }
    }
    stage('Deploy'){
      step{
        echo "Deploying"
      }
    }
  }
  post{
    success{
      echo "Success"
    }
    failure{
      echo "failure"
    }
  }
}
