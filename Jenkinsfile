pipeline {
  agent any
  stages {
    steps {
       script {
         File myfile = new File(""/tmp/newfile.txt")
         myfile.write("hi team ")
         println "content is ${myfile.txt}"
        }
      } 
    }
  }
}
