pipeline {
agent any
stages{

stage ('Build'){
steps{
sh ' sleep 20 ; echo "this is a build stage" '
}


stages{

stage ('Deply'){
steps{
sh '''
 sleep 20 
 echo "this is a Deploy stage" 
'''

}

stages{

stage ('Test'){
steps{
sh ' sleep 20 ; echo "this is a test stage" '
}


}






}



}