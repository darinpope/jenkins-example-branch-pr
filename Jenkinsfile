pipeline {
  agent any
  stages {
    stage('for main branch') {
      where {
        branch 'main'
      }
      steps {
        echo 'main branch'
      }
    }
  }
}