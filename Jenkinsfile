pipeline {
  agent any
  stages {
    stage('git clone') {
      steps {
        git(url: 'https://github.com/hiteshsp/java-app.git', branch: 'master')
      }
    }
  }
}