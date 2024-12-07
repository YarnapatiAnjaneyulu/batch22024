pipeline {
  // agent server1/any/dockeragent/kubernetes
  agent any
  stages {
    stage("working with conditions") {
      steps {
        script {
          a=1
          while(a<=10) {
            println "value of a is ${a}"
            a = a + 1
          }

          for(i=1;i<=10:i++) {
            println "value of i is ${i}"
          }
          
          lis1=[10,20,30,40]
          for(ele in list1){
            println "my ele is ${ele}"
          }
          
        }
      }
    }
  }
}
