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
        bat "copy index.html C:/Users/yajwi/OneDrive/Desktop/jenkins_assignment/"
      }
    }
   
  }
  
  
}
