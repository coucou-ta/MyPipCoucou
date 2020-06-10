pipeline {
  agent any
  stages {
    stage('AUTO') {
      parallel {
        stage('AUTO') {
          steps {
            build(propagate: true, job: 'TA_SELF_SERVICE_MYTF1')
          }
        }

        stage('AUTO2') {
          steps {
            echo 'coucou'
          }
        }

      }
    }

    stage('AUT3') {
      steps {
        echo 'tyty'
      }
    }

  }
}