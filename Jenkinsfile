pipeline {
   agent any
   
   environment {
       DEMO='1.3'
   }

   stages {
      stage('stage-1') {
         steps {
            writeFile file: 'test.txt', text: 'Test content'
            sh 'cat test.txt'
         }
      }
   }
}
