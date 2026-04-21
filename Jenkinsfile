pipeline {
  agent any
  stages {
    stage('Phase 1') {
      parallel {
        stage('Phase 1') {
          steps {
            echo 'Phase 1 started'
          }
        }

        stage('Phase 1.1') {
          steps {
            echo 'Phase 1.1 started'
          }
        }

        stage('Phase 1.2') {
          steps {
            echo 'Phase 1.2 started'
          }
        }

      }
    }

    stage('Phase 2') {
      parallel {
        stage('Phase 2') {
          steps {
            echo 'Phase 2 started'
          }
        }

        stage('') {
          steps {
            echo 'Phase 2.1 started'
          }
        }

      }
    }

    stage('End') {
      steps {
        echo 'End of pipeline'
      }
    }

  }
}