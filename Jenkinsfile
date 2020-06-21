pipeline {
   agent any
   stages {
      stage('First Step') {
         steps { 
            bat 'sh -c mvn -B -DskipTests clean package'
         }   
      }
   }  
   
}
