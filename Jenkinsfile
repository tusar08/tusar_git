pipeline {
  agent any
  stages {
    stage('stg1') {
      steps {
        sh 'echo "Anything"'
        echo 'hello'
        sh 'echo "type 2020"'
      }
    }

    stage('stg2') {
      steps {
        sh 'echo "test stg2"'
      }
    }

    stage('stg3') {
      steps {
        echo 'printing stg3'
      }
    }

  }
}