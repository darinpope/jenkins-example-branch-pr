pipeline {
  agent any
  stages {
    stage('for main branch') {
      when {
        branch 'main'
      }
      steps {
        echo 'main branch'
      }
    }
    stage('for OUMAR branch') {
      when {
        branch 'backend-v2.0'
      }
      steps {
        echo 'OUMAR branch'
      }
    }
    stage('for pull request') {
      when {
        changeRequest()
      }
      steps {
        echo 'pull request'
      }
    }
  }
}
