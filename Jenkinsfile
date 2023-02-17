pipeline {
  agent any
  stages {
    stage('working with file operations') {
      steps {
        script {
           File file = new File("/tmp/mydata.txt")
          
           file.write("Hi Team I am writting data from jenkins") 
        }
      }
    }
  }
}
