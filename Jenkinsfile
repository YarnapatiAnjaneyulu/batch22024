pipeline {
 // agent server1/any/dockeragent/kubernetes
 agent any
 parameters {
  choice choices: ['dev','sit','uat','pt','preprod','prod'], description: 'select the environment ', name: 'ENV'
}
 stages {
   stage("working with variables") {
     steps {
         script {
           var1=100
           println "var1 value is ${var1}"
           println "WORKSPACE iS ${WORKSPACE}"
           println "BUILD_NUMBER is ${BUILD_NUMBER}"
           println "my environment selected is ${params.ENV}"
         }
       }
     }
   } 
}
