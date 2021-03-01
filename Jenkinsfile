pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
    }

  }
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