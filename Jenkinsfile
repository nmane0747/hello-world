pipeline {
  agent {
    any {
      image 'maven:3-alpine'
      label 'docker'
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