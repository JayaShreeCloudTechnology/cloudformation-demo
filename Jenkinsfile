pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name infosys-auto-hyd-stack-1 --template-body file://simplests3cft.json --region 'us-east-1'"
              }
             }
            }
            }
