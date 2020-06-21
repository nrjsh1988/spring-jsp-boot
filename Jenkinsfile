pipeline {
   agent any
   stages {
      stage('First Step') {
         steps { 
            sh 'mvn -B -DskipTests clean package'
         }   
      }
   }  
   
}
