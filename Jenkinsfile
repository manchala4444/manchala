node{
  stage('SCM checkout'){
   git 'https://github.com/manchala4444/manchala.git'
   }
   stage('compile-package'){
   def mvnHome = tool name: 'maven-3', type: 'maven'
   sh "${mvnHome}/bin/mvn package"
   }

}
