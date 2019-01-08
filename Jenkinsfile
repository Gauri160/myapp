node{
 stage('SCM Checkout'){
  git 'https://github.com/Gauri160/myapp'
 } 
 stage('Comple-package'){
  def mvnHome =  tool name: 'apache-maven-3.6.0', type: 'maven'
  sh '${mvnHome}/bin/mvn package'
 }
}
