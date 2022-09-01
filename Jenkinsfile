pipeline {
  agent any
  triggers { 
    cron('*/15 * * * *')
  }
  stages {
    stage('STAGE ONE') {
      steps {
        echo ' This is stage ONE'
        sleep 3
      }
    }
  }
}
