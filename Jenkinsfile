pipeline {
agent any 
  stages {
    stage('Submit Repo') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmiEc2InstanceStack --template-body file://ec2-instance.yaml --region 'us-east-1'"
      }
    }
  }

}


