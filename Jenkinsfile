node{
   stage('SCM Checkout'){
     git 'https://github.com/saikumar13/Adhoc'
   }
   stage('Compile-package'){
   def mvnhome = tool name: 'MAVEN3.5', type: 'maven'
   sh "${mvnhome}/bin/mvn package"    
   }
}
