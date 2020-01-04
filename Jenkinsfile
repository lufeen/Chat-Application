node {

stage('SCM') {
 //git clone
  git 'https://github.com/lufeen/Chat-Application.git'
  }
  stage ('build the packages') {
  //mvn package
  sh 'mvn package'
  }
  stage ('archivel') {
  //archiving artifacts
   archiveArtifacts 'target/*.jar'
   }
 }
 
