pipeline {
  agent any
  stages {
    stage('check') {
      steps {
        git(url: 'https://github.com/jenkinsci/blueocean-plugin.git', branch: 'master')
      }
    }

  }
}