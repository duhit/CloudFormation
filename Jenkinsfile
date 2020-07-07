pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ec2-single-instance --template-body file://ec2-single-instance.json --region 'us-east-1'"
              }
             }
            }
            }
