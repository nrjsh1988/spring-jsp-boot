pipeline {
   agent any
   stages {
      stage('First Step') {
         steps { 
            bat 'mvn -B -DskipTests clean package'
         }   
      }
   }  
   post {
    always {
      cleanWs deleteDirs: true
    }
  }
}
