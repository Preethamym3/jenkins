pipeline {
agent any
stages{

   stage ('Build'){
   steps{
  sh ' sleep 20 ; echo "this is a build stage" '
   }
   }



   stage ('Deply'){
    steps{
     sh '''
      sleep 20 
      echo "this is a Deploy stage" 
      '''
         }
        }



     stage ('Test'){
      steps{
      sh ' sleep 20 ; echo "this is a test stage" '
           }


         }






}



}