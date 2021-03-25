pipeline{
agent any
stages{
  stage('build'){
   when{
    changeRequest title: "swe-pr"
     }
   steps{
     echo "hi all"
   }
  }
 }
 }
