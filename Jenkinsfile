  pipeline {
    agent any
    stages {
      stage('working with conditions') {
         steps {
           script {
            var1 = input message: 'Enter var1 value', parameters: [string(name: 'VAR1', trim: true)]
            If (var1.toInterger() == 10) {
              println "my var1 value is 10"
            }
            else {
              println "my var1 value is not 10"
            }
         }
       }
     }
   }
 }
   
