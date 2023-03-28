pipeline{
  agent any
  stages{
    stage('Create Instance'){
      steps{
        sh "aws cloudformation create-stack --stack-name nico-cloudformation --template-body file://cloud.yaml --region 'us-east-1'"
      }
    }
  }
}