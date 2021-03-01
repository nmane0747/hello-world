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

    stage('after buzz') {
      steps {
        echo 'after buzz'
      }
    }

    stage('input') {
      steps {
        input(message: 'wait for input', ok: 'go ahead', submitter: 'me', submitterParameter: 'Manager')
        echo 'agter inpuy'
      }
    }

  }
}