pipeline {
  agent any
  stages {
    stage('Debut') {
      steps {
        echo 'D�but Pipeline'
      }
    }

    stage('Run') {
      steps {
        sh 'java  Main.java'
      }
    }

    stage('Fin') {
      steps {
        echo 'Fin Pipeline'
      }
    }

  }
}