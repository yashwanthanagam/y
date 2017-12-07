pipeline {
 agent any
 parameters {
    choice(choices: 'Integration'\n'a'\n'b', description: '', name: '')
    booleanParam(name: 'DEBUG', defaultValue: false, description: 'check the box if you want to debug')
  //booleanParam(name: 'DEPLOY', defaultValue: false, description: 'check the box if you want to deploy')
    string(name: 'yash', defaultValue: 'Default ', description: 'Select.')


 }

 stages {
     stage('Example') {
         steps {
             echo "Hello ${params.ENVIRONMENT}"
         }
     }
 }
}
