pipeline {
  agent any
  stages {
    stage('fetch code') {
      steps {
        git(url: 'https://github.com/H-H-bin/qcom-mbn-tools.git', branch: 'master', changelog: true, poll: true, credentialsId: 'jenkins_auth')
      }
    }
  }
}