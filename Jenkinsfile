pipeline {
   agent any

   stages {
      stage('Hello') {
         steps {
            sh 'docker build . -t dojo-java:db'
            sh 'echo developer'
         }
      }
   }
}
