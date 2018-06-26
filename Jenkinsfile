node{

   stage('SCM Checkout'){
     git 'https://github.com/praveenlnx/ex-test'
   }
   stage('Compile-Package'){
      // Get maven home path
     sh 'mvn package'
   } 

}
