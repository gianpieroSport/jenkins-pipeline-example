pipeline {
  agent any
  stages {
    stage('') {
      steps {
        echo 'Hello pipeline'
        sh 'echo $(kubectl get deployment -n sophia2020 | grep atop)'
      }
    }

  }
}