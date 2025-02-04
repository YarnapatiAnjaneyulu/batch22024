pipeline {
  agent any
  stages {
    stage('working with file IO') {
      steps {
        script {
         File myfile = new File("/tmp/newfile.txt")
         myfile.write("hi team ")
         println "content is ${myfile.txt}"
        }
      } 
    }
  }
}
