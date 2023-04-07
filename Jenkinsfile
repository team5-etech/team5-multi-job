pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               echo "Building Artifact"

               sh 'systemctl status jenkins'
              

           }
       }
      stage('Deploy Code') {
          steps {
               echo "Deploying Code"
          }
      }
   }
}
