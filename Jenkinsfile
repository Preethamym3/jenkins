pipeline {
agent none
stages{

   stage ('Build'){
   agent {label 'node1'}
   steps{
  sh ' sleep 20 ; echo "this is a build stage" '
   }
   }



   stage ('Deply'){
   agent {label 'master'}
    steps{
     sh '''
      sleep 20 
      echo "this is a Deploy stage" 
      '''
         }
        }



     stage ('Test'){
     agent {label 'node1'}
      steps{
      sh ' sleep 20 ; echo "this is a test stage" '
           }


         }

}



}