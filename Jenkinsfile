pipeline {
  agent any
  stages {
    stage('stage1') {
      parallel {
        stage('stage1') {
          steps {
            echo 'stage 1 running '
            sh '''ls -lh /opt
echo \'list\''''
          }
        }

        stage('parallel stage 1') {
          steps {
            echo 'stage 1 paralle file test'
          }
        }

      }
    }

  }
}