pipeline {
  agent any
  stages {
    stage('checkout code') {
      steps {
        git(url: 'origin git@github.com:kaka83/bashScripting.git', branch: 'master', changelog: true)
      }
    }

  }
}