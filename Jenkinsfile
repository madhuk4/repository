def myfn() {
    println "function is been called"
}

pipeline {
  agent any
  stages {
     stage('working with functions') {
       steps {
         script {
           myfn()
         }
       }
     }
   }
 }
