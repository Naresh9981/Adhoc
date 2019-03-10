node{
   stage('SCM Checkout'){
     git 'https://github.com/saikumar13/Adhoc'
   }
   stage('Compile-package'){
   sh "${mvnhome}/bin/mvn package"    
   }
}
