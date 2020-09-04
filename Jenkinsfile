pipeline {
  agent any
  stages {
    stage('Check/Create ATOP') {
      steps {
        sh 'hasTOP= kubectl get -n sophia2020 deployment | grep atop'
        sh 'echo $aTOP'
      }
    }

  }
}