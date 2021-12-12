pipeline{
agent any
  stages{
  stage("git") 
     {
      steps{
        git branch:'main', url:'https://github.com/teghdeep/testing.git'
      }
    }
    stage("copy") 
     {
      steps{
        bat 'copy https://raw.githubusercontent.com/tpandhi/jenkin_assignment/main/index.html C:/Users/yajwi/OneDrive/Desktop/jenkins_assignment'
      }
    }
   
  }
  
  
}
