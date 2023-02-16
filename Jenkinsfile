def myfn() {
    println "function is been called"
}
def myadd (int a = 10, int b = 20) {
    sum = a + b
    println "add of ${a} and ${b} is ${sum}"
}

pipeline {
  agent any
  stages {
     stage('working with functions') {
       steps {
         script {
           myfn()
           myadd (100,200)
           myadd
           myadd (b = 3 , a = 1)
         }
       }
     }
   }
 }
