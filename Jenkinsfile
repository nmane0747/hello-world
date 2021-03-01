pipeline {
  agent {
    docker {
      image 'helloworld'
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