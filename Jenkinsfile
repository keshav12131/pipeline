pipeline{
 agent any
  stages{
    stage (build){
    steps{
     bat 'echo "Hello"'
    }
    }
  }
 post{
 failure{
  bat 'echo "Failedddd"' 
 }
 }
}
