pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name rdscheck --template-body file://rds.yaml --region 'ap-south-1'
            }
            }
        }
    }
