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
        echo 'Copy..'
      }
    }
   
  }
  
  
}
