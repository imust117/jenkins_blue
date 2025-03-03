pipeline {
  agent any
  stages {
    stage('check') {
      parallel {
        stage('check') {
          steps {
            git(url: 'https://github.com/jenkinsci/blueocean-plugin.git', branch: 'master')
          }
        }

        stage('task1') {
          steps {
            sh 'echo "task1"'
          }
        }

      }
    }

    stage('build') {
      steps {
        build '23344'
      }
    }

  }
}