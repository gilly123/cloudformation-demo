pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket2 --template-body file://simples3cft.json --region 'us-east-2'"
              }
             }
            }
            }
