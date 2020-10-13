pipeline{
 agent any
  stages{
   stage (build){
    steps{
     bat 'echo "Hello"
    }
    }
  }
 post{
  always{
  bat 'echo "Completed"' 
  }
 }
}
