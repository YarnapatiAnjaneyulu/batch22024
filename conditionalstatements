pipeline {
  // agent server1/any/dockeragent/kubernetes
  agent any
  stages {
    stage("working with conditions") {
      steps {
        script {
          a=10
          b=20
          if(a>b) {
             println "value of a is ${a}"
          }
          else {
            println "value of b is big ${b}"
          }
        }
      }
    }
  }
}
