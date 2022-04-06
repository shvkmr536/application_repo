pipeline {
  agent any
  stages {
    stage('SCM Checkout') {
      steps {
        git(url: 'https://github.com/shvkmr536/jenkins-terraform', branch: 'master')
      }
    }

  }
  environment {
    TERRAFORM_HOME = 'tool \'myTerraform\''
    EXAMPLE_KEY = 'credentials(\'aws-cred\')'
  }
}