pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               echo "Building Artifact"
               sh 'systemctl jenkins status'

           }
       }
      stage('Deploy Code') {
          steps {
               echo "Deploying Code"
          }
      }
   }
}
