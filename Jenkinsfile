pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name tcs-demo-test-hyd-bucket --template-body file://simplests3cft.json --region 'us-west-1'"
              }
             }
            }
            }
