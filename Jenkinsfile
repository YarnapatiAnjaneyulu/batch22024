def myfn(){
  println "Hi Team welcome to jenkins functions "
}
def mycode(a,b){
  sum=a+b
  println "sum of a & b is ${sum}"
}
def mycode_default(i=10,j=20){
  println "i value is ${i},j value is ${j}"
}
pipeline {
  // agent server1/any/dockeragent/kubernetes
  agent any
  stages {
    stage("working with functions") {
      steps {
        script {
           myfn()
           mycode(10,20)
           mycode_default()
           mycode_default(200,400)
           mycode_default(150)
          }
        }
      }
    }
  }
