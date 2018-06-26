node{

   stage('SCM Checkout'){
     git 'https://github.com/praveenlnx/ex-test'
   }
   stage('Compile-Package'){
      // Getting path for Maven
      def mvnHome =  tool name: 'maven-3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
   } 

}
