pipeline {
  agent any
  stages {
    stage('Debut') {
      steps {
        echo 'Début Pipeline'
      }
    }

    stage('Build and Run') {
      steps {
        sh '''







javac HelloWorld/Main.java'''
      }
    }

    stage('Fin') {
      steps {
        echo 'Fin Pipeline'
      }
    }

  }
}