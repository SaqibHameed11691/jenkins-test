pipeline {
  agent {
    node {
      label 'umair'
    }

  }
  stages {
    stage('build') {
      steps {
        build 'build'
      }
    }

  }
  environment {
    test = ''
  }
}