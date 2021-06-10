pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            echo 'msg 1'
            sleep 30
          }
        }

        stage('stage2') {
          steps {
            echo 'msg2'
          }
        }

      }
    }

  }
}