pipeline {
  agent any
  stages {
    stage('buzzz') {
      parallel {
        stage('buzzz') {
          steps {
            echo 'buzz'
          }
        }

        stage('bees') {
          steps {
            echo 'bees bees'
          }
        }

      }
    }

  }
}