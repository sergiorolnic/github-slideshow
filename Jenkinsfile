pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'prova'
      }
    }

    stage('test') {
      parallel {
        stage('test') {
          steps {
            error 'ciso'
          }
        }

        stage('') {
          steps {
            catchError()
          }
        }

      }
    }

  }
}