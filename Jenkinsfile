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
  }
}