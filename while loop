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
        }
      }
    }
  }
}
