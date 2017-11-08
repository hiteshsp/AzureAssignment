pipeline {
  agent any
  stages {
    stage('git clone') {
      steps {
        git(url: 'https://github.com/hiteshsp/AzureAssignment.git', branch: 'master')
      }
    }
    stage('Maven build') {
      steps {
        sh 'echo "maven is built"'
      }
    }
  }
}