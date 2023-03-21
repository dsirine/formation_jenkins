pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'sh \'sudo apt-get -y update && sudo apt-get -y upgrade\''
      }
    }

    stage('stage2') {
      steps {
        sh 'sh \'dpkg -l > /tmp/paquets\''
      }
    }

  }
}