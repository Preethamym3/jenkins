pipeline {
agent none
stages{
  stage ('Build and Deploy'){
    parallel {
   stage ('Build'){
   agent {label 'node1'}
   steps{
  sh ' sleep 20 ; echo "this is a build stage" '
   }
   }




    stage ('Deploy'){
   agent {label 'node1'}
    steps{
     sh '''
      sleep 20 
      echo "this is a Deploy stage" 
      '''
         }
        }
}
}


     stage ('Test'){
     agent {label 'node2'}
      steps{
      sh ' sleep 20 ; echo "this is a test stage" '
           }


         }

}



}
