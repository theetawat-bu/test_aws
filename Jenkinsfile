pipeline {
  agent {
    node {
      label 'demo'
    }

  }
  stages {
    stage('Checkout Code') {
      steps {
        git(url: 'https://github.com/theetawat-bu/test_aws', branch: 'main', changelog: true)
      }
    }

  }
  environment {
    start = '1'
  }
}