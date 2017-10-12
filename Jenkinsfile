pipeline {
  agent any
  stages {
    stage('SCM') {
      steps {
        git(url: 'https://github.com/davek804/aggravation', branch: 'develop', changelog: true, poll: true)
      }
    }
  }
}