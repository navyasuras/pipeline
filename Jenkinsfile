pipeline {
  agent any
  stages {
    stage('dev') {
      parallel {
        stage('dev') {
          steps {
            echo 'devolepment stage'
          }
        }

        stage('test') {
          steps {
            echo 'testing stage'
          }
        }

        stage('plugin') {
          steps {
            echo 'plugin stage'
          }
        }

      }
    }

    stage('QA') {
      steps {
        echo 'qa stage'
      }
    }

    stage('UAT') {
      steps {
        echo 'uat stage'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploy stage'
      }
    }

    stage('operate') {
      steps {
        echo 'operate stage'
      }
    }

  }
}