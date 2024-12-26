pipeline{
  agent any
  stages{
    stage('breakfast'){
      steps{
        echo "I am having breakfast"
      }
    }
    stage('workout'){
      steps{
        echo "I am doing my workout"
      }
    }
    stage('study'){
      steps{
        echo "I am studying"
      }
    }
    stage('family_time'){
      steps{
        echo "Enjoying with family"
      }
    }
    stage('play'){
      steps{
        echo "Playing"
      }
    }
  }
  post{
    success{
      echo "My day went well"
    }
  }
}
