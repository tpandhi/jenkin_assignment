pipeline{
agent any
  stages{
  stage("git") 
     {
      steps{
        git branch:'main', url:'https://github.com/tpandhi/jenkin_assignment.git'
      }
    }
    stage("copy") 
     {
      steps{
        bat ' copy index.html C:\Users\yajwi\OneDrive\Desktop\jenkins_assignmnet'
      }
    }
   
  }
  
  
}
