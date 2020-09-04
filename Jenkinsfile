pipeline {
  agent any
  stages {
    stage('Check/Create ATOP') {
      steps {
        sh 'export hasTOP= kubectl get -n sophia2020 deployment | grep atop'
      }
    }

  }
}