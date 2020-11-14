pipeline {
  agent any
  stages {
    stage('Install') {
      steps {
        sh 'npm install',
        echo 'Instalando'
     }
    }

    stage('Test') {
        steps {
        echo 'Test'
        }
    }

    stage('Build') {
      steps {
        echo 'build .... OK'
      }
    }
  }
}

