pipeline {
  agent any
  stages {
    stage('Bulding') {
      steps {
        echo 'Help me'
      }
    }

    stage('Test1') {
      parallel {
        stage('Test1') {
          steps {
            echo 'HE'
          }
        }

        stage('Test2') {
          steps {
            echo 'She'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Zeze'
      }
    }

  }
}