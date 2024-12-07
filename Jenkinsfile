pipeline {
  // agent server1/any/dockeragent/kubernetes
  agent any
  stages {
    stage("working with variables") {
      steps {
         script {
           var1=100
             println "var1 value is ${var1}"
             println "BRANCH_NAME iS ${BRANCH_NAME}"
             println "BUILD_NUMBER is ${BUILD_NUMBER}"
          }
        }
      }
    }
  }
}  



