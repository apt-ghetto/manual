pipeline {
  agent {
    dockerfile true
  }
  stages {
    stage('Build the manual') {
      steps {
        git 'https://github.com/apt-ghetto/manual.git'
        sh 'make latexpdf'
      }
    }
  }
}
